Here’s your updated **README.md** with MongoDB configuration, API endpoints, and your video link.  

---

### **📦 Product API - Spring Boot with MongoDB**
This is a **Spring Boot REST API** for managing products using **MongoDB** as the database.

🔗 **Live API:** [Product API](https://5an9v1-8080.bytexl.dev/products)  
🎥 **Demo Video:** [Watch Here](https://drive.google.com/file/d/1Wv6kYSuUqjgx3g2jkb382MRzd1gRVTDb/view?usp=sharing)  
🌐 **GitHub Repository:** [Product API GitHub](https://github.com/shivaP192/product-management)

---

## **📌 Features**
- 🗄️ Uses **MongoDB** as the database
- 🌐 RESTful API for **CRUD operations** on products
- 🔥 Built with **Spring Boot**

---

## **⚙️ Installation & Setup**
### **1️⃣ Clone the Repository**
```sh
git clone https://github.com/yashdongre12/product.git
cd product
```

### **2️⃣ Configure MongoDB in `application.properties`**
Update your **MongoDB credentials** in `src/main/resources/application.properties`:
```properties
spring.data.mongodb.host=bytexldb.com
spring.data.mongodb.port=5050
spring.data.mongodb.database=db_43asngdub
spring.data.mongodb.username=user_43asngdub
spring.data.mongodb.password=p43asngdub
spring.data.mongodb.authentication-database=admin
```

### **3️⃣ Run the Application**
```sh
mvn spring-boot:run
```

---

## **🛠️ API Endpoints**
| Method | Endpoint               | Description                  |
|--------|------------------------|------------------------------|
| **GET**    | `/api/products`         | Get all products             |
| **GET**    | `/api/products/{id}`    | Get product by ID            |
| **POST**   | `/api/products`         | Add a new product            |
| **PUT**    | `/api/products/{id}`    | Update a product by ID       |
| **DELETE** | `/api/products/{id}`    | Delete a product by ID       |

---

## **📜 Product Model**
```json
{
  "id": "string",
  "name": "string",
  "price": "number"
}
```

---

## **💡 Contributing**
Feel free to contribute by submitting **issues** or **pull requests**.
