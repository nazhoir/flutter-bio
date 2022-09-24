## Membuat Image

jalankan kode dibawah untuk membuat image docker

docker build -t (nama image):(tag) .

jangan lupa untuk menampahkan titik(.) di akhir kode

contoh :
docker build -t nazhoir/bio:v1.0 .


## Membuat container

Tuliskan perintah kode berikut di command line
docker run -d -p (port) (nama image dan tag)
penjelasan :
-d : untuk menjalankan dibacground
-p : untuk menjalanakn di port yang diinginkan 

contoh :
docker run -d -p 80:80 nazhoir/bio:v1.0