-Truy cập route secure - thành công
Method: GET
URL: http://localhost:3000
Key: Authorization
Kết quả: "Welcome! Visit first public resource."
![alt text](<public/images/Screenshot 2025-09-25 191119.png>)

-Truy cập route public -thành công
Method: GET
URL: http://localhost:3000/public
Kết quả: "Welcome! Visit second public resource."
![alt text](<public/images/Screenshot 2025-09-25 190953.png>)

-Truy cập route / - thành công
Method: GET
URL: http://localhost:3000
Kết quả: "Welcome! Visit first public resource."
![alt text](<public/images/Screenshot 2025-09-25 190851.png>)


test  cookie_auth.js
-Truy cập route login - thành công
Method: POST
URL: http://localhost:3001/login
Kết quả: "Logged in!"
![alt text](<public/images/Screenshot 2025-09-25 191248.png>)

-Truy cập route login -sai mật khẩu
Method: POST
URL: http://localhost:3001/login
Kết quả: "Invalid credentials"
![alt text](<public/images/Screenshot 2025-09-25 195120.png>)

-Truy cập route profile - thành công
Method: GET
URL: http://localhost:3001/profile
Kết quả: "Welcome user 1, your cookie is valid."
![alt text](<public/images/Screenshot 2025-09-25 194413.png>)

-Truy cập route profile - cookie hết hạn
Method: GET
URL: http://localhost:3001/profile
Kết quả: "No cookie found"
![alt text](<public/images/Screenshot 2025-09-25 195325.png>)

-Truy cập route logout - thành công
Method: POST
URL: http://localhost:3001/logout
Kết quả: "Logged out."
![alt text](<public/images/Screenshot 2025-09-25 195747.png>)