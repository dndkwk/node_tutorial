# node_tutorial
node.js 공부

MySQL, MongoDB 및 시퀄라이즈 사용

<br> require('./routes/index.js')와 require('./routes')는 같다.
<br> app.use()와 router.route()로 연결할 때 주소가 합쳐진다.
<br> res.render('sequelize',{users})는 sequelize.ejs를 렌더링해서 보내겠다는 의미
<br> router.route()를 이용해 한번에 많은 method 구현 가능
<br> populate() : ObjectID를 해당 도큐먼트의 값으로 바꿔줌