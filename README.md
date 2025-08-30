## An AI-powered tool that automatically generates SEO-optimized articles tailored for your niche. It handles keyword research, content structuring, and SEO best practices — saving hours of manual effort.

# ✨ Features

🔑 Keyword-based generation – Enter your target keyword(s) and get SEO-optimized content.

📝 AI-powered writing – Generates human-like, engaging articles.

📊 SEO optimization – Includes meta description, headings (H1–H3), and keyword density check.

🔄 Automated workflow – Built using n8n for scheduling and multi-step automation.

🔍 Semantic search integration – Ensures content is relevant and aligns with search intent.

📑 Export options – Save articles as Markdown, HTML, or directly to CMS.

# 🛠️ Tech Stack

n8n
 – Workflow automation.

OpenAI API
 – AI content generation.

Supabase
 – Semantic search + embeddings.

Node.js
 – Backend logic and API handling.


# 🚀 Getting Started
1️⃣ Clone the Repository
git clone https://github.com/yourusername/automated-seo-article.git
cd automated-seo-article

2️⃣ Install Dependencies
npm install

3️⃣ Setup Environment Variables

Create a .env file:

OPENAI_API_KEY=your_openai_api_key
SUPABASE_URL=your_supabase_url
SUPABASE_KEY=your_supabase_key

4️⃣ Run n8n
n8n start

5️⃣ Generate Your First Article

Run the workflow with your target keyword:

node src/generateArticle.js --keyword "AI in Healthcare"

<img width="1408" height="952" alt="image" src="https://github.com/user-attachments/assets/c3d616fa-5bb9-4de9-bc0a-8edf368b7481" />


# 📌 Example Output

Keyword: "AI in Healthcare"

Title: How AI is Transforming Healthcare in 2025

Meta Description: Explore the impact of Artificial Intelligence on modern healthcare systems, patient outcomes, and future innovations.

Headings:

H1: AI in Healthcare: Revolutionizing Patient Care

H2: Benefits of AI in Diagnostics

H2: AI in Drug Discovery

H3: Real-World Use Cases

# 🔒 Security & Rate Limiting

Workspace-based isolation for users.

API rate limiting to prevent abuse.

Secure API key management.

# 🧩 Future Improvements

Multi-language article support 🌍

Automatic internal linking 🔗

SERP analysis integration 📈

# 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss.
