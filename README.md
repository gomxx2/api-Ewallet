# api-Ewallet
Technical Test Fullstack Developer

1. extract api_e-wallet.rar
2. put in you dir local server (example: xampp/htdocs)
3. setup your .env
4. php artisan migrate

testing(postman recommended)
1. for create user using this curl 
curl --location --request POST 'http://localhost:8000/v1/create?name=henti&mother_name=puji astuti&job=pengarah&saldo=7500'

2. for view data using this curl 
curl --location --request GET 'http://localhost:8000/v1/'

3. for topup
curl --location --request POST 'http://localhost:8000/v1/topup?users_id=2&saldo=45000'

4. for sending
curl --location --request POST 'http://localhost:8000/v1/transfer?sender_id=2&amount=45000&receiver_id=1'

additional
- sorry for using rar format not repo because iam using office computer, where this computer connected with office github account not mine. (its complicated if change with my github account)
