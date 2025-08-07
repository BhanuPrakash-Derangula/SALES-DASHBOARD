# Sales Essentials Dashboard

A comprehensive CRM sales dashboard built with Next.js 15, React 18, and modern web technologies.

## 🚀 Features

- **📊 Interactive Charts**: Bar charts, pie charts, and funnel visualizations using Recharts
- **📱 Responsive Design**: Fully responsive layout that works on all devices
- **🎨 Modern UI**: Clean, professional interface with Tailwind CSS and shadcn/ui components
- **📈 Real-time Data**: Mock data with realistic sales metrics and KPIs
- **🔍 Search Functionality**: Global CRM search capability
- **📋 Export Features**: Data export functionality
- **🎯 Multi-Dashboard**: Tabbed interface for different dashboard views

## 🛠️ Tech Stack

- **Next.js 15** - React framework with App Router
- **React 18** - Frontend library
- **TypeScript** - Type safety
- **Tailwind CSS** - Utility-first CSS framework
- **shadcn/ui** - Modern UI component library
- **Recharts** - Composable charting library
- **Lucide React** - Beautiful icon library
- **Radix UI** - Accessible component primitives

## 📦 Installation

### Prerequisites
- Node.js 18+ 
- npm, yarn, or pnpm

### Setup Instructions

1. **Extract the project files**
   \`\`\`bash
   unzip sales-essentials-dashboard.zip
   cd sales-essentials-dashboard
   \`\`\`

2. **Install dependencies**
   \`\`\`bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   \`\`\`

3. **Run the development server**
   \`\`\`bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   \`\`\`

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 📊 Dashboard Features

### Revenue Metrics
- **Revenue Won**: $12.3K display card
- **Revenue Lost**: $6.2K display card

### Interactive Charts
- **Deal Win/Loss Percentage**: Progress bars showing 66.67% won, 33.33% lost
- **Open Deal Value by Stage**: Funnel chart with color-coded stages
- **Contacts by Sales Owner**: Bar chart showing contact distribution
- **Tasks by Owner**: Grouped bar chart for open vs completed tasks
- **Forecasted Revenue**: Stacked bar chart by deal stage and quarter
- **Revenue by Source**: Pie chart showing email, organic, and paid sources

### Navigation
- **Top Navigation**: Search, notifications, profile, trial information
- **Sidebar**: Icon-based navigation for different CRM sections
- **Dashboard Tabs**: Switch between Sales Essentials, Sales Dashboard, Activities Dashboard
- **Bottom Tabs**: Summary, Deals, Contacts, Sales activities, Revenue breakdown

## 📁 Project Structure

\`\`\`
├── app/
│   ├── globals.css          # Global styles and Tailwind imports
│   ├── layout.tsx           # Root layout component
│   └── page.tsx             # Main dashboard page
├── components/
│   └── ui/                  # shadcn/ui components
│       ├── avatar.tsx
│       ├── badge.tsx
│       ├── button.tsx
│       ├── card.tsx
│       ├── input.tsx
│       └── tabs.tsx
├── lib/
│   └── utils.ts             # Utility functions
├── next.config.mjs          # Next.js configuration
├── tailwind.config.ts       # Tailwind CSS configuration
├── tsconfig.json           # TypeScript configuration
└── package.json            # Dependencies and scripts
\`\`\`

## 🎨 Design System

- **Colors**: Professional blue, green, and red color palette
- **Typography**: Clean, readable fonts with proper hierarchy
- **Spacing**: Consistent spacing using Tailwind's spacing scale
- **Components**: Reusable UI components with shadcn/ui
- **Icons**: Lucide React icons for consistency
- **Charts**: Recharts with custom styling and animations

## 🔧 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License.

## 🙏 Acknowledgments

- [Next.js](https://nextjs.org/) - The React framework
- [shadcn/ui](https://ui.shadcn.com/) - UI component library
- [Tailwind CSS](https://tailwindcss.com/) - CSS framework
- [Recharts](https://recharts.org/) - Chart library
- [Lucide](https://lucide.dev/) - Icon library

---

**Built with ❤️ using Next.js and modern web technologies**
