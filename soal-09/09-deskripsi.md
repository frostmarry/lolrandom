-hal pertama yang saya lakukan adalah melakukan clone dari github.com/sgnd/todo, kemudian mengubah namanya menjadi "dumbways-kloter1-todo" untuk disamakan dengan repo yang ada pada heroku.

-lalu masuk kedalam repository local "dumbways-kloter1-todo" dengan perintah cd, selanjutnya login akun heroku agar repository local bisa terhubung dengan repository yang ada pada heroku. 

-menginstall addons postgresql dan mengganti konfig production dengan data yang bisa dilihat pada `heroku config`

-menghapus 1 baris pada Procfile agar tidak terjadi seeder error

-kemudian melakukan commit dan push ke heroku master
