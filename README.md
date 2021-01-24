# echo_API
Goのフレームワークechoを触ってみた。<br>
APIサーバー<br>
パラメータを受けっとりJSONで返す。<br>
server_get getパラメータでJSONを返す。<br>
server_post postパラメータでJSONを返す。<br>

go run hello.go<br>
http://localhost:1323/ にアクセスでHello,Worldと表示される。<br>

go run server_get.go (go run server_post.go) <br>
http://localhost:1323/user?name=oku_echo&email=foovar@gmail.comにアクセスすると<br>
{"name":"oku_echo","email":"foovar@gmail.com"}というようにJSONが帰ってくる。<br>
