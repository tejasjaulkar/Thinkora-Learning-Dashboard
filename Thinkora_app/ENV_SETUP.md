# Environment Setup for AI Features

## Required Environment Variables

Create a `.env` file in the `server` directory with the following variables:

```env
# Server Configuration
PORT=5001
NODE_ENV=development

# Database Configuration (use your existing MongoDB connection)
MONGODB_URL=mongodb+srv://root:Tej%40s476@cluster0.r1ok0.mongodb.net/Thinkora

# JWT Configuration (use your existing secret)
JWT_SECRET=your-jwt-secret-key

# Cloudinary Configuration (use your existing keys)
CLOUDINARY_API_KEY=your-cloudinary-api-key
CLOUDINARY_API_SECRET=your-cloudinary-api-secret
CLOUDINARY_CLOUD_NAME=your-cloudinary-cloud-name

# Razorpay Configuration (use your existing keys)
RAZORPAY_KEY_ID=your-razorpay-key-id
RAZORPAY_SECRET=your-razorpay-secret

# Email Configuration (use your existing email settings)
MAIL_HOST=smtp.gmail.com
MAIL_PORT=587
MAIL_USER=your-email@gmail.com
MAIL_PASS=your-email-password

# CORS Configuration
CORS_ORIGIN=["http://localhost:3000"]

# NEW: AI Configuration
OPENAI_API_KEY=your-openai-api-key
```

## Getting OpenAI API Key

1. Go to [OpenAI Platform](https://platform.openai.com/)
2. Sign up or log in to your account
3. Navigate to "API Keys" section
4. Create a new API key
5. Copy the key and paste it in your `.env` file

## Starting the Application

1. **Start the server:**
   ```bash
   cd server
   npm run dev
   ```

2. **Start the client (in a new terminal):**
   ```bash
   npm start
   ```

3. **Or use the combined command:**
   ```bash
   npm run dev
   ```

## Testing AI Features

1. **AI Chat**: Look for the floating robot button in the bottom-right corner
2. **AI Dashboard**: Click "AI Hub" in the navigation bar
3. **AI Recommendations**: Go to AI Dashboard → AI Recommendations tab
4. **AI Analytics**: Go to AI Dashboard → Learning Analytics tab
5. **AI Quiz Generator**: Go to AI Dashboard → Quiz Generator tab (Instructors only)

## Troubleshooting

- If AI features don't work, check that your OpenAI API key is correctly set
- Ensure you have sufficient OpenAI API credits
- Check the browser console and server logs for any errors
- Make sure all dependencies are installed correctly 