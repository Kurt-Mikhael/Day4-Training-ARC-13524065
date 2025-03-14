# Day4-Training-ARC-13524065'
1. Buka filenya
2. Kemudian, perhatikan hal-hal apa saja yang perlu dicapai untuk menyelesaikan kasusnya.
   Objectives
   - Complete the network documentation.
   - Perform basic device configurations on a router and a switch.
   - Verify connectivity and troubleshoot any issues.
3. Kita akan menyesuaiakan konfigurasi ip dari router (College), switch (ClassA dan ClassB) dan PC Hosts (Student 1,2,3, dan 4)
4. Kita lihat bahwa classB tidak memiliki IP default gateaway, supaya jaringan yang jalan, kita hubungkan default gateaway dengan router, yaitu dengan interface g0/1.
5. Perhatikan bahwa student1 dan student2 dihubungkan dengan switch classA yang dihubungkan dengan interface g0/0, kita hubungkan IP default gateaway students1 dan students2 dengan IP adress g0/0.
6. Perhatikan bahwa student3 dan student4 dihubungkan dengan switch classB yang dihubungkan dengan interface g0/1, kita hubungkan IP default gateaway students3 dan students4 dengan IP adress g0/1.
7. Setelah itu, kita konfigurasikan IPv6 default gateaway dari students1, students2, students3, dan students4 berdasarkan tabel yang telah diberikan
