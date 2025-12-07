Create a comprehensive student benefits web portal for university students in Germany pursuing an MSc in AI & Robotics

## Research Requirements

Research and include 50+ platforms offering free or discounted access to students across these categories:

### 1. AI & Machine Learning Tools
- GitHub Copilot Pro (free via GitHub Education Pack, worth $228/year)
- Google Gemini AI Pro (12 months free for students, includes Gemini 3 Pro, Deep Research, NotebookLM Plus, 2TB storage, worth €240/year, verified via SheerID)
- Perplexity Pro (1 month free + up to 24 months via referrals, includes Study Mode, multiple AI models)
- ChatGPT Plus (periodic limited-time offers, check chatgpt.com/students)

### 2. Developer Tools
- GitHub Student Developer Pack (90+ partner tools, GitHub Pro, Copilot Pro, 180 core-hours Codespaces/month, total value $13,000+, valid 2 years renewable)
- JetBrains All Products Pack (All IDEs free - IntelliJ IDEA, PyCharm, WebStorm, CLion, DataGrip, Rider, worth €779/year, 40% graduation discount)
- Namecheap (Free .me domain + SSL certificate for 1 year via GitHub Pack)
- DigitalOcean ($200 platform credits for 1 year via GitHub Pack)

### 3. Cloud & Infrastructure
- Microsoft Azure for Students ($100 credits annually renewable, 25+ always-free services, Azure OpenAI access, no credit card required)
- AWS Educate (Free cloud training, hands-on labs, career pathways, promotional credits)
- Google Cloud Platform ($300 credits for 90 days for new users)
- MongoDB Atlas ($200 credits via GitHub Pack, plus always-free tier with 512MB storage)

### 4. Design & Creative Tools
- Figma Education (Professional plan free for 2 years, unlimited files, version history, Dev Mode, FigJam, worth $180/year)
- Canva for Education (Pro features free via Canva for Campus - institution-dependent)
- Adobe Creative Cloud (60%+ student discount, ~€20/month first year, 20+ apps)
- Autodesk Education (1-year free access to AutoCAD, Fusion 360, Maya, 3ds Max, 100+ tools, worth €2,000+/year)

### 5. Productivity & Apps
- Notion Education Plus (Free Plus plan with unlimited pages/blocks, 30-day version history, worth $120/year)
- Microsoft 365 Education (Free Word, Excel, PowerPoint, OneNote, Teams, 1TB OneDrive)
- 1Password (Free Families plan via GitHub Pack for 5 members, worth $60/year)
- Bitwarden (Always free open-source password manager)

### 6. Entertainment & Lifestyle Discounts
- Spotify Premium Student (50% off ~€5/month, valid up to 4 years)
- Apple Music Student (50% off €5.99/month, includes free Apple TV+, up to 48 months)
- Amazon Prime Student (6 months free trial, then 50% off €4.49/month)
- YouTube Premium Student (~50% off €7.49/month)
- Apple Education Store (Up to 10% off MacBooks/iPads, free AirPods during back-to-school)
- Samsung Education (Up to 30% off Galaxy devices)

## Portal Features

### UI/UX Requirements
1. **Tab-based navigation** (NOT scroll-based) with tabs for:
   - About & Guide (default tab)
   - AI Tools
   - Developer
   - Cloud
   - Design
   - Apps
   - Discounts

2. **Search functionality** at the top of the tabs that filters across all benefit cards

3. **Light/Dark mode toggle** with:
   - Default to light theme
   - Saved preference in localStorage
   - Smooth transition between themes

4. **NO hero section** - start directly with search and tabs

5. **Modern, clean design** with:
   - Rounded corners (12-16px radius)
   - Subtle shadows
   - Category-colored accents for cards
   - Mobile-responsive (single column on mobile)
   - Professional typography (Plus Jakarta Sans + JetBrains Mono)

### About & Guide Tab Content
Include comprehensive information:

1. **What Is This?** - Explanation of the portal and its purpose

2. **Why Should You Use These?** - Key reasons:
   - Save €5,000+ annually
   - Access professional tools used at top tech companies
   - Build portfolio projects with enterprise-grade resources
   - Learn industry-standard tools before entering job market
   - Get free cloud credits for AI/ML projects
   - Access cutting-edge AI assistants

3. **How Verification Works** - Three methods:
   - Email Verification (@student.berlinsbi.com)
   - SheerID (upload student ID or enrollment letter)
   - GitHub Education (verify once, unlock 90+ tools)

4. **Pro Tips for Maximum Value** (8 tips):
   - Start with GitHub Student Developer Pack first (gateway to 90+ tools)
   - Set renewal reminders 30 days before expiration
   - Link GitHub, Microsoft, Google education accounts
   - Keep school email active even after graduation
   - Export data before subscriptions expire
   - Check regional availability (Germany has good coverage)
   - Stack benefits together (Azure + GitHub + JetBrains + Copilot)
   - Use for portfolio projects to impress employers

5. **Important Notes** - Disclaimers and last verified date

### Benefit Cards
Each card should include:
- Logo/icon with category-colored background
- Badge (FREE, DISCOUNT, CREDITS, etc.)
- Title and description
- Feature tags (3-4 key features)
- Value indicator (monetary worth and terms)
- Two buttons: "Get Access →" and "Guide"
- Hover effects (lift, glow, border color change)
- Search data attribute for filtering

### Individual Guides (Modal)
Create detailed step-by-step guides for EVERY tool including:

1. **What You Get** section - Detailed explanation of benefits

2. **How to Get It** section with numbered steps:
   - Step 1: Where to go
   - Step 2: How to sign up
   - Step 3: How to verify
   - Step 4: How to activate/download

3. **Pro Tip** - Specific advice for that tool (e.g., "Use PyCharm for AI/ML work", "Use NotebookLM for study guides")

### Technical Requirements
- Single HTML file with embedded CSS and JavaScript
- No external dependencies except Google Fonts
- Mobile-first responsive design
- CSS variables for theming
- Smooth animations and transitions
- Keyboard accessible (Escape to close modals)
- Click outside the modal to close

### Verification Methods to Document
1. **SheerID** - Used by Google, Perplexity, Autodesk, Adobe, Spotify, YouTube
2. **School email domain** - Direct verification via .edu or school email
3. **GitHub Education** - Gateway verification for 90+ partner tools
4. **UNiDAYS** - Used by Apple services
5. **Manual upload** - Student ID, enrollment letter, or class schedule

### Stats to Display
- €5,000+ total annual value
- 50+ free tools
- 100% legitimate offers

### Footer
- Last updated date
- Disclaimer about verifying on official websites
- Not affiliated with BSBI notice
