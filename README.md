# api-otentikasi
api otentikasi



# Development
1.  Java 17
2.  Maven
3.  Spring boot
4.  mysql
5.  Spring tool suite 4


# API

1. http://localhost:8005/auth/registrasi endpoint untuk registrasi pengguna (email, password, fullName) /POST
2. http://localhost:8005/auth/login endpoint untuk menerima data login (email, password)  /POST
3. http://localhost:8005/users endpoint untuk mengambil daftar pengguna /GET
4. http://localhost:8005/users/me endpoint untuk mengambil data pengguna berdasarkan token  /GET

# Configuration
1. Buat username 'root' dan password ''
2. Buat database dengan nama 'jwtduazsolusi'

# Run
java -jar /target/auth-api-0.0.1-SNAPSHOT.jar
