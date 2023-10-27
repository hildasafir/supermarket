# supermarket
capstone_2_supermarket_Hilda

**1. Case Study**
Sebuah supermarket telah melaksanakan total enam kampanye pemasaran selama tiga tahun terakhir. Untuk meningkatkan tingkat jumlah sales perusahaan melalui kampanye yang efektif, perusahaan bermaksud untuk menganalisis kampanye yang telah dilaksanakan berdasarkan prinsip segmentasi, posisi, dan penargetan. Analisis ini diharapkan akan membantu tim pemasaran dalam merumuskan strategi bisnis yang tepat.

Segmentasi melibatkan pembagian basis pelanggan menjadi kelompok-kelompok yang berbeda berdasarkan karakteristik khusus, seperti demografi, perilaku, atau preferensi. Posisi berhubungan dengan cara perusahaan menyajikan produk atau layanan dalam pasar, mempertimbangkan faktor-faktor seperti harga, kualitas, dan citra merek. Penargetan adalah proses mengidentifikasi segmen pelanggan yang paling relevan dan menyesuaikan upaya pemasaran untuk mencapai dan melibatkan segmen tersebut dengan efektif.

Dengan menganalisis kampanye-kampanye terdahulu melalui sudut pandang ini, perusahaan bertujuan untuk mendapatkan wawasan tentang apa yang paling berhasil dan memahami segmen pelanggan mana yang paling responsif. Wawasan ini akan membantu tim pemasaran menciptakan kampanye yang lebih terarah dan sukses di masa depan, yang pada akhirnya akan berkontribusi pada pertumbuhan bisnis.

**2. Problem Statement**
Sebagai seorang analis data, kita akan mencoba menjawab pertanyaan berikut:

Perusahaan ingin mengetahui, dari kampanye-kampanye yang telah dilaksanakan dari 1 hingga 6, kampanye mana yang paling sukses, dan faktor-faktor apa yang memengaruhi kesuksesan kampanye-kampanye tersebut sehingga mereka dapat mengembangkan strategi pemasaran berikutnya yang berkontribusi pada peningkatan sales?

untuk menjawab pertanyaan tersebut maka perlu mengindentifikasi hal ini:

1. Campaign manakah yang paling banyak mendapatkan response yang baik?
2. Campaign manakah yang memiliki jumlah pembelian terbanyak  berdasarkan produk yang dibeli?
3. Campaign terbaik, Apa jenis produk yang paling diminati oleh konsumen di setiap keluarga ?
4. Campaign terbaik, Siapa yang paling banyak melakukan pembelian di setiap jenis produk berdasarkan umur?
5. Campaign terbaik, bagaimana perilaku konsumen terhadap diskon?

# **Data Explanation**

**People**
-   ID: Customer's unique identifier
-   Year_Birth: Customer's birth year
-   Education: Customer's education level
-   Marital_Status: Customer's marital status
-   Income: Customer's yearly household income
-   Kidhome: Number of children in customer's household
-   Teenhome: Number of teenagers in customer's household
-   Dt_Customer: Date of customer's enrollment with the company
-   Recency: Number of days since customer's last purchase
-   Complain: 1 if the customer complained in the last 2 years, 0 otherwise

**Products**
-   MntWines: Amount spent on wine in last 2 years
-   MntFruits: Amount spent on fruits in last 2 years
-   MntMeatProducts: Amount spent on meat in last 2 years
-   MntFishProducts: Amount spent on fish in last 2 years
-   MntSweetProducts: Amount spent on sweets in last 2 years
-   MntGoldProds: Amount spent on gold in last 2 years

**Promotion**
-   NumDealsPurchases: Number of purchases made with a discount
-   AcceptedCmp1: 1 if the customer accepted the offer in the 1st campaign, 0 otherwise
-   AcceptedCmp2: 1 if the customer accepted the offer in the 2nd campaign, 0 otherwise
-   AcceptedCmp3: 1 if the customer accepted the offer in the 3rd campaign, 0 otherwise
-   AcceptedCmp4: 1 if the customer accepted the offer in the 4th campaign, 0 otherwise
-   AcceptedCmp5: 1 if the customer accepted the offer in the 5th campaign, 0 otherwise
-   Response: 1 if the customer accepted the offer in the last campaign, 0 otherwise

**Place**
-   NumWebPurchases: Number of purchases made through the company’s website
-   NumCatalogPurchases: Number of purchases made using a catalog
-   NumStorePurchases: Number of purchases made directly in stores
-   NumWebVisitsMonth: Number of visits to the company’s website in the last month

**Numerical & Categorical**
- Ordinal : Educational
- Nominal : Marital_Status, Complain, AcceptedCmp1, AcceptedCmp2, AcceptedCmp3, AcceptedCmp4, AcceptedCmp5, Response
- Discrete: Kidhome, Teenhome, MntWines, MntFruits, MntMeatProducts, MntFishProducts, MntSweetProducts, MntGoldProds, NumDealsPurchases, NumWebPurchases, NumCatalogPurchases, NumStorePurchases, NumWebVisitsMonth, Recenc
- Continue: Year_Birth, Age, Income
- Datetime : Dt_Customer**3. Description Data Set**
