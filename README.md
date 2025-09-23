Jadi disini akan berisi dokumentasidariku sendiri

cara setup project mobile apps menggunakan react native dan di styling menggunakan tailwind css, 


Langkah - Langkah : 

1. Build react native dengan expo
   -> npx create-expo-app@latest MyApp
   
   setelah proses instalasi selesai tinggal lu jalanin aja
   npx expo start

2. Konfigurasi dengan nativewind

   -> ikuti dokumentasi dari nativewind dengan benar
   -> create metro.config.js  (npx expo customize      
metro.config.js)  
   -> jangan lupa install react-native-reanimate

   -> pasang plugin ke babel.config.js
    plugins: ["react-native-reanimated/plugin"]

   -> udah deh tinggal jalanin aja aplikasi lu