# MODUL 4
## Nomor 1
Untuk menemukan node 8, 6 dan 7

Current Node: (3,d=0), Previous Node: None

Current Node: (4,d=1), Previous Node: (3,d=0)

Current Node: (2,d=1), Previous Node: (3,d=0)

Current Node: (5,d=2), Previous Node: (4,d=1)

Current Node: (6,d=2), Previous Node: (4,d=1)

Current Node: (1,d=2), Previous Node: (2,d=1)

Current Node: (7,d=3), Previous Node: (5,d=2)

Current Node: (8,d=3), Previous Node: (6,d=2)

1. Pada langkah pertama, BFS mulai dari node 3. Node-node tetangga dari node 3 adalah node 4 dan node 2. Oleh karena itu, BFS akan mengeksplorasi node 4 dan 2 terlebih dahulu.
2. Pada langkah kedua, BFS mengeksplorasi node 4, yang memiliki tetangga node 5 dan node 6. Node 5 dan 6 belum dijelajahi, sehingga BFS akan terus mengeksplorasi node-node tersebut sebelum kembali ke node 2.
3. Pada langkah ketiga, BFS mengeksplorasi node 5, yang memiliki tetangga node 7 dan node 8. Node 7 dan 8 belum dijelajahi, sehingga BFS akan terus mengeksplorasi node-node tersebut sebelum kembali ke node 6.
4. Setelah selesai mengeksplorasi node-node yang lebih jauh dari node 5 (yaitu node 7 dan 8), BFS akan kembali ke node 6.
5. Selanjutnya, BFS akan mengeksplorasi node 6, yang juga memiliki tetangga node 7 dan node 8. Karena kedua node ini telah dijelajahi, BFS tidak perlu melanjutkan penjelajahan lebih jauh dari node 6.
6. Akhirnya, BFS akan kembali ke node 2, dan dari sana, ke node 1.

Dengan demikian, BFS akan mengeksplorasi semua node-node dalam graf yang dapat dijangkau dari node awal (node 3), termasuk node-node 8, 6, dan 7, sesuai dengan langkah-langkah penjelajahan secara bertahap yang telah dijelaskan di atas.

## Nomor 2
Untuk menemukan Node 5

Current Node: (0,d=0), Previous Node: None

Current Node: (1,d=1), Previous Node: (0,d=0)

Current Node: (2,d=1), Previous Node: (0,d=0)

Current Node: (3,d=2), Previous Node: (1,d=1)

Current Node: (4,d=2), Previous Node: (1,d=1)

Current Node: (5,d=2), Previous Node: (2,d=1)

Current Node: (6,d=2), Previous Node: (2,d=1)

Untuk menjelaskan bagaimana BFS menemukan Node 5, berikut adalah langkah-langkahnya:

1. Node 0 adalah node awal (sumber) dalam pencarian BFS. Pada langkah pertama, BFS mulai dari node 0.

2. Node-node tetangga langsung dari node 0 adalah node 1 dan node 2. Oleh karena itu, pada langkah kedua, BFS akan menjelajahi node 1 dan 2.

3. Node 1 adalah salah satu tetangga dari node 0. Pada langkah ketiga, BFS akan menjelajahi node 1. Node-node tetangga langsung dari node 1 adalah node 3 dan node 4. Oleh karena itu, pada langkah keempat, BFS akan menjelajahi node 3 dan 4.

4. Pada langkah kelima, BFS akan menjelajahi node 3. Node 5 adalah salah satu tetangga dari node 3. Karena node 5 belum dijelajahi (berwarna putih), BFS akan menjelajahi node 5.

5. Setelah menemukan node 5, BFS akan melanjutkan dengan node lain dalam antrian penjelajahan.

Jadi, BFS menemukan Node 5 dengan menjelajahi node-node sesuai dengan prinsip penjelajahan secara lebar, yang berarti akan menjelajahi semua tetangga langsung dari node awal (node 0) terlebih dahulu sebelum menjelajahi node-node lebih jauh.

## Nomor 3
Untuk menemukan Node 9
Current Node: (1,d=0), Previous Node: None

Current Node: (2,d=1), Previous Node: (1,d=0)

Current Node: (3,d=1), Previous Node: (1,d=0)

Current Node: (4,d=1), Previous Node: (1,d=0)

Current Node: (5,d=2), Previous Node: (2,d=1)

Current Node: (6,d=2), Previous Node: (2,d=1)

Current Node: (7,d=2), Previous Node: (4,d=1)

Current Node: (8,d=2), Previous Node: (4,d=1)

Current Node: (9,d=3), Previous Node: (5,d=2)

Current Node: (10,d=3), Previous Node: (5,d=2)

Current Node: (11,d=3), Previous Node: (7,d=2)

Current Node: (12,d=3), Previous Node: (7,d=2)
Proses BFS dalam menemukan node 9 adalah sebagai berikut:

1. Node 1 adalah node awal (sumber) dalam pencarian BFS. Pada langkah pertama, BFS dimulai dari node 1.

2. Node-node tetangga langsung dari node 1 adalah node 2, 3, dan 4. Oleh karena itu, pada langkah kedua, BFS akan menjelajahi node 2, 3, dan 4.

3. Pada langkah ketiga, BFS menjelajahi node 2. Node-node tetangga langsung dari node 2 adalah node 5 dan 6. Oleh karena itu, pada langkah keempat, BFS menjelajahi node 5 dan 6.

4. Pada langkah kelima, BFS menjelajahi node 5. Node-node tetangga langsung dari node 5 adalah node 9 dan 10. Node 9 belum dijelajahi (berwarna putih), jadi BFS menjelajahi node 9. Ini adalah saat node 9 ditemukan.

5. Setelah menemukan node 9, BFS akan melanjutkan menjelajahi node-node lain dalam antrian penjelajahan.

Jadi, BFS menemukan node 9 dengan cara menjelajahi node-node sesuai dengan prinsip penjelajahan secara lebar, yang berarti akan menjelajahi semua tetangga langsung dari node awal (node 1) terlebih dahulu sebelum menjelajahi node-node lebih jauh. Node 9 ditemukan saat semua tetangga langsung dari node 5 telah dijelajahi.

## Nomor 4
Proses BFS dalam menemukan node C dalam contoh yang Anda berikan adalah sebagai berikut:
Current Node: (F,d=0), Previous Node: None

Current Node: (B,d=1), Previous Node: (F,d=0)

Current Node: (G,d=1), Previous Node: (F,d=0)

Current Node: (A,d=2), Previous Node: (B,d=1)

Current Node: (D,d=2), Previous Node: (B,d=1)

Current Node: (I,d=2), Previous Node: (G,d=1)

Current Node: (C,d=3), Previous Node: (D,d=2)

Current Node: (E,d=3), Previous Node: (D,d=2)

Current Node: (H,d=3), Previous Node: (I,d=2)

1. Node F adalah node awal (sumber) dalam pencarian BFS. Pada langkah pertama, BFS dimulai dari node F.

2. Node-node tetangga langsung dari node F adalah node B dan G. Oleh karena itu, pada langkah kedua, BFS akan menjelajahi node B dan G.

3. Pada langkah ketiga, BFS menjelajahi node B. Node-node tetangga langsung dari node B adalah node A dan D. Oleh karena itu, pada langkah keempat, BFS menjelajahi node A dan D.

4. Pada langkah kelima, BFS menjelajahi node D. Node-node tetangga langsung dari node D adalah node C dan E. Node C belum dijelajahi (berwarna putih), jadi BFS menjelajahi node C. Ini adalah saat node C ditemukan.

5. Setelah menemukan node C, BFS akan melanjutkan menjelajahi node-node lain dalam antrian penjelajahan.

Jadi, BFS menemukan node C dengan cara menjelajahi node-node sesuai dengan prinsip penjelajahan secara lebar, yang berarti akan menjelajahi semua tetangga langsung dari node awal (node F) terlebih dahulu sebelum menjelajahi node-node lebih jauh. Node C ditemukan saat semua tetangga langsung dari node D telah dijelajahi.
