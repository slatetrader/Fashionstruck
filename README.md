
# 1. Clone starter into a NEW folder
git clone https://github.com/your-username/fashionstruck-reset.git fashionstruck

# 2. Go inside
cd fashionstruck

# 3. Install deps
npm install
# 4. Add your repo as "origin"
git remote add origin https://github.com/YOUR-USERNAME/fashionstruck.git

# 5. Push the code
git branch -M main
git push -u origin main
git clone https://github.com/your-username/fashionstruck-fullstack.git
cd fashionstruck-fullstack
npm install
MONGODB_URI=mongodb+srv://USER:PASS@cluster.mongodb.net/fashionstruck?retryWrites=true&w=majority
STRIPE_SECRET_KEY=sk_test_…
STRIPE_PUBLISHABLE_KEY=pk_test_…
vercel --prod
