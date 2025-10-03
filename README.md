# 🛒 Super Store Sales Analysis Using EDA  

## 📌 Project Overview  
Superstore merupakan ritel berskala besar yang menjual beragam produk dengan harga kompetitif. Namun, skala bisnis yang luas sering menghadirkan tantangan dalam menjaga profitabilitas.  

Melalui **Exploratory Data Analysis (EDA)**, proyek ini bertujuan untuk:  
- Mengidentifikasi area lemah dalam bisnis (produk, wilayah, strategi diskon).  
- Mengeksplorasi pola penjualan dan profitabilitas.  
- Memberikan insight dan rekomendasi strategi untuk meningkatkan efisiensi serta keuntungan.  

---

## 🎯 Objectives  
- Mengetahui kategori produk dengan profit rendah.  
- Mengidentifikasi wilayah/segmen pelanggan yang kurang menguntungkan.  
- Menganalisis pengaruh diskon terhadap profit.  
- Memberikan rekomendasi strategi berbasis data.  

---

## 📊 Dataset  
Dataset berisi transaksi penjualan superstore dengan informasi seperti:  
- **Order Details**: Order ID, Order Date, Ship Date, Ship Mode  
- **Customer Info**: Customer ID, Segment, Region  
- **Product Info**: Category, Sub-Category, Product Name  
- **Sales Performance**: Sales, Quantity, Discount, Profit  

---

## 🛠️ Tools & Technologies  

### 🔹 Languages  
- Python  
- SQL  

### 🔹 Libraries & Frameworks  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Plotly  

### 🔹 Tools  
- Google Colab / Jupyter Notebook  
- Excel / Google Sheets  
- Git & GitHub  

---

## 📈 Key Insights & Visualizations  

### 🔹 Profitabilitas Produk  
- **Top 3 Produk Merugi**: Sub-kategori tertentu menunjukkan kerugian terbesar.  
- **Top 3 Produk Untung**: Produk tertentu menjadi penyumbang profit terbesar.  

<img width="1606" height="702" alt="image" src="https://github.com/user-attachments/assets/86204abd-6ce3-4343-8ec6-940793df60e3" />
<img width="984" height="584" alt="image" src="https://github.com/user-attachments/assets/591d6d5c-8b8e-484d-832c-c9bc7a6f6652" />
<img width="1183" height="684" alt="image" src="https://github.com/user-attachments/assets/91e01790-70c0-43f2-b3b3-eb806d51c0c9" />
<img width="1183" height="684" alt="image" src="https://github.com/user-attachments/assets/2aebf00d-0152-4a08-af3d-30fa55e50c7c" />



---

### 🔹 Profit Berdasarkan Region  
- Profit tidak merata antar region.  
- Ada region yang lebih dominan dalam memberikan keuntungan kumulatif.  

*(Visualisasi: Bar chart total profit per region)*  

---

### 🔹 Profit Berdasarkan State  
- **Top 10 States**: Penyumbang keuntungan terbesar.  
- **Bottom 10 States**: Mengalami kerugian paling besar.  

*(Visualisasi: Bar chart top & bottom 10 states)*  

---

## ✅ Summary  
- Beberapa produk memberikan penjualan tinggi namun **profit rendah**.  
- Diskon berlebihan justru **mengurangi profitabilitas**.  
- Tidak semua region dan state memberikan kontribusi positif terhadap profit.  

**Rekomendasi:**  
1. Optimalkan strategi diskon agar tidak merugikan.  
2. Fokus pada produk dengan margin tinggi.  
3. Tingkatkan strategi pemasaran pada region dan state yang berpotensi.  

---

## 🚀 How to Run the Project  
1. Clone repository ini:  
   ```bash
   git clone https://github.com/username/Super-Store-Sales-Analysis-Using-EDA.git
   cd Super-Store-Sales-Analysis-Using-EDA
