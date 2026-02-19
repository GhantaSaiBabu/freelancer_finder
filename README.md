🚀 SB Works – Freelancer Finder (Smartinternz Project)A professional full-stack MERN application designed to bridge the gap between clients and freelancers. This project facilitates seamless project posting, competitive bidding, and efficient team collaboration.Team ID: LTVIP2026TMIDS37879Status: In-Development (SmartInternz Group Project)🛠 Tech StackLayerTechnologyFrontendReact.js, Bootstrap, Material UI, AxiosBackendNode.js, Express.jsDatabaseMongoDB, MongooseAuthenticationJWT (JSON Web Tokens), bcrypt.jsDev ToolsPostman, MongoDB Compass, VS Code⚙️ Key FeaturesSecure Authentication: Multi-role login (Client, Freelancer, Admin) with JWT protection.Project Lifecycle: Clients can post projects; Freelancers can bid on active listings.Dynamic Dashboards: Personalized views for managing bids, projects, and profiles.Admin Control: Moderation tools to ensure platform integrity.Resource Management: Real-time data fetching using REST APIs.👨‍💻 Project TeamTeam Leader: 👑 Ghanta Sai Babu – Backend Architecture & Full Stack IntegrationTeam Members: 👤 Kowthavarapu Kesav – Frontend Development & UI/UX 👤 Pathan Rasool Meharaj Khan – API Development & Database Design 👤 V Harshitha – Testing, Documentation & Quality Assurance📦 Getting StartedPrerequisitesNode.js (v16+)MongoDB Local or Atlas AccountGit1. InstallationBash# Clone the repository
git clone https://github.com/GhantaSaiBabu/freelancer_finder.git
cd freelancer_finder

# Install Backend dependencies
cd server && npm install

# Install Frontend dependencies
cd ../client && npm install
2. Environment SetupCreate a .env file in the /server directory:Code snippetPORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
3. Run the ApplicationBash# Start Server (from /server)
npm start

# Start Client (from /client)
npm start
Open http://localhost:3000 to view the app.📌 API OverviewMethodEndpointDescriptionPOST/api/auth/registerUser RegistrationPOST/api/auth/loginUser AuthenticationGET/api/projectsFetch all available projectsPOST/api/projectsPost a new job (Client only)POST/api/bidsSubmit a project bid📂 Project ResourcesDemo & Documentation: 🔗 Google Drive FolderLive Preview: 🔗 Recorded Demo🔮 Future Roadmap: Real-time Chat (Socket.io), Payment Integration (Stripe/Razorpay), Mobile App (React Native), and Freelancer Rating System.
