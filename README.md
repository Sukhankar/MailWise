# MailWise - AI Email Reply Generator ✉️🤖

MailWise is a Chrome extension that integrates seamlessly with Gmail to generate AI-powered email replies, saving time and enhancing productivity. 🚀

## 🛠️ Setup and Installation

### Backend (Spring Boot)

1. **Clone the repository**
   ```sh
   git clone https://github.com/your-repo/mailwise-backend.git
   cd mailwise-backend
   ```

2. **Build and run the backend**
   ```sh
   mvn clean install
   mvn spring-boot:run
   ```
   Or, run with Docker:
   ```sh
   docker build -t mailwise-backend .
   docker run -p 8080:8080 mailwise-backend
   ```

3. **Deployed API Endpoint:**  
   ```
   https://demo-deployment-latest-9em1.onrender.com/api/email/generate
   ```

---

### Frontend (React + Vite)

1. **Clone the frontend repository**
   ```sh
   git clone https://github.com/your-repo/mailwise-frontend.git
   cd mailwise-frontend
   ```

2. **Install dependencies**
   ```sh
   npm install
   ```

3. **Update API URL in `App.jsx`**
   ```jsx
   const response = await axios.post("https://demo-deployment-latest-9em1.onrender.com/api/email/generate", {
     emailContent,
     tone
   });
   ```

4. **Run the frontend**
   ```sh
   npm run dev
   ```

5. **Deployed Frontend:**  
   [MailWise Live](https://mail-wise.vercel.app/)

## 🎯 How It Works
1. Enter the email content.
2. Select the desired tone (Professional, Casual, Friendly).
3. Click "Generate Reply."
4. Copy and use the AI-generated email instantly!

📩 Happy emailing with MailWise! 🚀

