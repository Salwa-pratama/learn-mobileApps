// Kotlin kompiler
Jadi kotlin itu sebelum dijalankan / proses development dia masih menggunakan jdk atau java development kit, dan apabila kita ingin ngerun
maka kita harus ngecomile file .kt jadi file .jar agar bisa dibaca oleh java runtime nya

# Cara ngerun

-> konlinc Main.kt utils/Hello.kt -include-runtime -d Main.jar

-> kotlinc . -include-runtime -d Main.jar

# Run

kalo udah di compile sekarang bisa di run menggunakan kode dibawah

-> java -jar Main.jar
