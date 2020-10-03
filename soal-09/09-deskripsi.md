- hal pertama yang saya lakukan adalah melakukan clone dari github.com/sgnd/todo, kemudian mengubah namanya menjadi "dumbways-kloter1-todo" untuk disamakan dengan repo yang ada pada heroku.

- lalu masuk kedalam repository local "dumbways-kloter1-todo" dengan perintah cd, selanjutnya login akun heroku agar repository local bisa terhubung dengan repository yang ada pada heroku. 

![1](https://github.com/frostmarry/lolrandom/blob/main/soal-09/01.png)

- menginstall addons postgresql dan mengganti konfig production dengan data yang bisa dilihat pada `heroku config`

![2](https://github.com/frostmarry/lolrandom/blob/main/soal-09/02.png)

![3](https://github.com/frostmarry/lolrandom/blob/main/soal-09/03.png)

- menghapus 1 baris pada Procfile agar tidak terjadi seeder error

![4](https://github.com/frostmarry/lolrandom/blob/main/soal-09/04.png)

- kemudian melakukan commit dan push ke heroku master

![5](https://github.com/frostmarry/lolrandom/blob/main/soal-09/05.png)

Hasilnya:

[dumbways-kloter1-todo](https://dumbways-kloter1-todo.herokuapp.com/)
