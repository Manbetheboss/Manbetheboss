- 👋 Hi, I’m @Manbetheboss
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<res.setHeader('Content-Type', 'text/plain');

Manbetheboss/Manbethebossh is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
---// src/services/api.js
import axios from 'axios';

const API_URL = 'http://localhost:5000';

export const getUserProfile = async () => {
  const response = await axios.get(`${API_URL}/user-profile`);
  return response.data;
};

// Add other API functions as needed
