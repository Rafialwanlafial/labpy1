# latihan2
Untuk mencari bilangan terbesar dari 3 buah bilangan, algoritma di atas membandingkan terlebih dulu apakah a > b.
Jika a > b, maka ada 2 kandidat bilangan terbesar, yaitu a dan c sehingga perlu dilakukan pengujian yang manakah dari a dan c yang lebih besar dengan melakukan membandingkan nilai b dan c. Jika nilai b ternyata lebih besar dari c, maka bilangan terbesar adalah a. Nilai terbesar adalah c jika ternyata c lebih besar dari a.
Jika kondisi a > b tidak terpenuhi (atau b <= a), maka 2 kandidat bilangan terbesar adalah b dan c. Jika nilai c ternyata lebih kecil dari a, maka b adalah nilai terbesar, sedangkan jika c yang lebih besar dari b, maka yang terbesar adalah c.
