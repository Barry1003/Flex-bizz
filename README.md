# Flex Bizz — Social E-commerce for Small Businesses

**What Flex Bizz does (short):**  
Flex Bizz is a social-first e-commerce platform where small business owners showcase products, share short video promos, and build customer relationships — all in one interactive feed. Buyers can discover products through social interactions (likes, comments, shares), follow stores, and make purchases without leaving the social experience.

---

## Why this matters
Many small sellers struggle to reach customers and build trust. Flex Bizz combines the discovery power of social media with simple e-commerce tools so businesses can convert engagement into sales quickly. It reduces friction for buyers and helps sellers showcase products in a more authentic, social way.

---

## Who it's for
- Micro and small business owners who want a simple, social storefront.
- Buyers who prefer discovery and social proof before buying.
- Marketers and creators who want to promote products via short videos and social posts.

---

## Key features
- **Social product feed:** Scrollable feed with product posts, short videos, and interactions (like, comment, share).  
- **Store profiles & networking:** Sellers have profiles where buyers can message, follow, and rate them.  
- **Instant add-to-cart & checkout:** Simple checkout with saved addresses and flexible payment options.  
- **Short video promos:** Sellers upload short videos (15–60s) to highlight products.  
- **Return policy reconfirmation:** When adding to cart, buyers see a short pop-up with the product’s return policy.  
- **Reviews & testimonials:** Customers can leave feedback to build credibility.  
- **Search & filters:** Fast product search and category filters for discovery.

---

## Technologies used (high level)
- Frontend: React + Next.js, Tailwind CSS  
- Backend: Node.js (Express or Nest.js)  for REST & real-time features  
- Database: PostgreSQL (primary), Redis (sessions, caching)  
- Realtime: WebSockets (Socket.io) or Pub/Sub (for chat & live notifications)  
- CI/CD: GitHub Actions for tests and deploys

---

## Quick start (developer)
1. Clone the repo: `git clone https://github.com/<your-username>/flex-bizz.git`
2. Install dependencies (example for Node):  
   - `cd flex-bizz`  
   - `cd frontend && npm install`  
   - `cd ../backend && npm install`
3. Copy env: `cp .env.example .env` and fill in database and auth secrets.
4. Run locally:  
   - `npm run dev` in frontend (Next.js)  
   - `npm run dev` in backend (Node)
5. Seed sample data (if provided): `npm run seed`
 
