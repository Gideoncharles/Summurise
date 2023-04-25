npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p

// Inside tailwind.config.js

/** @type {import('tailwindcss').Config} */
export default {
  Content: [
    "./index.html",
  "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {
      fontFamily: {
        satoshi: ["Satoshi", "sans-serif"],
        inter: ["Inter", "sans-serif"],
      }
    },
  },
  plugins[],
}
npm install react-redux

{
  const axios = require('axios');

const options = {
  method: 'GET',
  url: 'https://article-extractor-and-summarizer.p.rapidapi.com/summarize',
  params: {
    url: 'https://time.com/6266679/musk-ai-open-letter/',
    length: '3'
  },
  headers: {
    'content-type': 'application/octet-stream',
    'X-RapidAPI-Key': '370a901c0dmsh8a5178cac2ac7b3p1ec905jsn20aa0d05821d',
    'X-RapidAPI-Host': 'article-extractor-and-summarizer.p.rapidapi.com'
  }
};

try {
	const response = await axios.request(options);
	console.log(response.data);
} catch (error) {
	console.error(error);
}
}