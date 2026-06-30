# CARESPHERE WELLNESS

## Nairobi's Premier Health Governance & Care Coordination Platform

CARESPHERE WELLNESS is a comprehensive health advisory and care coordination platform that provides structured oversight, preventive risk management, and long-term health continuity for individuals, families, professionals, and organizations. Built as a full-stack web application, it bridges the gap between reactive healthcare and proactive health governance.

---

## Problem Statement

Modern healthcare is fundamentally fragmented. Patients interact with multiple providers—hospitals, specialists, laboratories, pharmacies, and insurance systems—without any centralized oversight. This reactive approach leads to delayed diagnoses, missed follow-ups, poor continuity of care, preventable emergencies, rising healthcare costs, and significant stress for individuals and families navigating complex medical decisions alone.

CARESPHERE WELLNESS solves this by providing a structured health governance framework that transforms healthcare from isolated reactions into continuous, intelligently coordinated health management.

---

## Project Goals & Purpose

### Primary Objectives

1. **Establish Health Governance** as a new standard in healthcare delivery
2. **Empower individuals and families** to stay ahead of health risks through intelligent oversight
3. **Coordinate care seamlessly** across all healthcare providers and touchpoints
4. **Provide preventive risk management** through early detection and structured planning
5. **Create a unified platform** for health advisory, e-commerce, and client engagement
6. **Become Africa's leading health governance partner** through technology-enabled service delivery

### Target Audience

- Professionals and executives
- Entrepreneurs and business owners
- Families and households
- Diaspora-supported families
- Individuals managing chronic conditions
- Couples planning pregnancy
- Small organizations and corporate teams

---

## Tools & Technologies

### Frontend Stack

| Technology | Purpose |
|------------|---------|
| React 18 | Component-based UI development with hooks and context API |
| TypeScript | Type-safe JavaScript for robust application logic |
| Bootstrap 5 | Responsive, mobile-first UI framework with custom theming |
| HTML5 + CSS3 | Semantic markup and advanced styling with CSS variables |
| Font Awesome 6 | Professional icon library for enhanced visual communication |
| SweetAlert2 | Interactive, accessible modal dialogs for user feedback |
| Flatpickr | Lightweight date and time picker for appointment scheduling |

### Backend Stack

| Technology | Purpose |
|------------|---------|
| Node.js | JavaScript runtime environment for server-side logic |
| Express.js | Web application framework for building RESTful APIs |
| Python (Flask) | Microservices for specific business logic and data processing |
| PostgreSQL | Relational database for structured data storage |
| Cloudinary | Cloud-based image management and CDN delivery |

### Infrastructure & DevOps

| Technology | Purpose |
|------------|---------|
| AWS (EC2, S3, RDS) | Cloud hosting, storage, and managed database services |
| Nginx | Web server and reverse proxy for load balancing |
| SSL/TLS | End-to-end encryption for secure data transmission |
| Git | Version control for collaborative development |

### Third-Party Integrations

| Service | Purpose |
|---------|---------|
| WhatsApp Business API | Instant client communication and appointment booking |
| M-Pesa | Mobile money payment processing (integration ready) |
| Google Maps API | Location services and office mapping |
| Calendly | Appointment scheduling and calendar management |
| Google Analytics | User behavior tracking and performance monitoring |

---

## Key Features

### 1. Health Governance Dashboard
- Centralized client health oversight
- Risk assessment tracking and reporting
- Care coordination workflow management
- Appointment scheduling and follow-up monitoring

### 2. Executive Health Risk Assessment
- Comprehensive health screening and risk mapping
- Chronic disease detection and prevention planning
- Personalized health intelligence reports
- 90-day health optimization roadmaps

### 3. Care Coordination System
- Automated appointment scheduling and reminders
- Specialist referral management
- Laboratory and diagnostic follow-up tracking
- Treatment monitoring and insurance navigation
- Second opinion facilitation

### 4. Premium Concierge Health Support
- 24/7 priority advisory access
- Hospital admission coordination
- Emergency healthcare navigation
- Family health oversight
- Diaspora family healthcare support
- Quarterly wellness reviews

### 5. ReproHub (Maternal & Preconception Advisory)
- Preconception risk screening
- Fertility and maternal health planning
- Nutrition and lifestyle optimization
- Pregnancy care coordination

### 6. Diaspora Family Support Portal
- Remote healthcare management for families abroad
- Medical updates and reporting
- Provider coordination and medication management
- Emergency support and continuous communication

### 7. E-Commerce Marketplace
- Curated selection of ergonomic and rehabilitative products
- Product filtering by category, price, and gender
- Shopping cart with persistent local storage
- Secure checkout with WhatsApp order confirmation
- M-Pesa integration ready
- Product reviews and ratings
- Wishlist functionality

### 8. Health Knowledge Hub (Blog)
- Evidence-based articles on preventive health
- Categories: Hypertension, Diabetes, Stress & Burnout, Maternal Health, Occupational Health, Executive Wellness, Lifestyle Diseases
- Search functionality and category filtering
- Social sharing capabilities
- Newsletter subscription for lead generation

### 9. Client Management
- User authentication and role-based access
- Profile management and health records
- Appointment history and status tracking
- Secure data handling compliant with Kenya Data Protection Act (2019)

### 10. Administrative Dashboard
- User and client management
- Content management for blog and products
- Analytics and reporting
- Service delivery metrics

---

## Responsive Design Features

- Mobile-first architecture ensuring seamless experience across all devices
- Adaptive typography that scales based on viewport size
- Touch-optimized UI components for mobile interaction
- Collapsible navigation with persistent cart visibility
- Responsive product grid with flexible card layouts
- Sticky navigation bars with scroll effects
- Optimized image delivery with lazy loading
- Accessible color contrast and interactive elements

---

## Security & Compliance

### Regulatory Standards

- **Kenya Data Protection Act (2019)**: Full compliance with data protection and privacy regulations
- **KMPDC Licensing**: Registered under Kenya Medical Practitioners and Dentists Council
- **HIPAA Alignment**: Adherence to healthcare data privacy standards
- **ISO 9001:2015**: Quality management system implementation
- **GDPR Ready**: European data protection standards for international clients

### Security Measures

- SSL/TLS encryption for all data transmission
- Role-based access control (RBAC)
- Secure authentication with JWT
- Data encryption at rest
- Regular security audits and penetration testing
- Professional indemnity coverage

---

## Project Structure

```
caresphere-wellness/
├── frontend/
│   ├── public/
│   │   ├── img/                    # Static images and assets
│   │   └── index.html              # Main HTML entry point
│   ├── src/
│   │   ├── components/             # Reusable React components
│   │   │   ├── common/
│   │   │   │   ├── Navbar.jsx
│   │   │   │   ├── Footer.jsx
│   │   │   │   └── CartSidebar.jsx
│   │   │   ├── pages/
│   │   │   │   ├── Home.jsx
│   │   │   │   ├── About.jsx
│   │   │   │   ├── Services.jsx
│   │   │   │   ├── Partners.jsx
│   │   │   │   ├── Blog.jsx
│   │   │   │   ├── Store.jsx
│   │   │   │   ├── Booking.jsx
│   │   │   │   ├── Checkout.jsx
│   │   │   │   └── Contact.jsx
│   │   │   └── dashboard/
│   │   │       ├── ClientDashboard.jsx
│   │   │       └── AdminDashboard.jsx
│   │   ├── styles/
│   │   │   └── style.css
│   │   ├── utils/
│   │   │   ├── api.js
│   │   │   └── validators.js
│   │   └── App.jsx
│   ├── package.json
│   └── README.md
├── backend/
│   ├── src/
│   │   ├── api/
│   │   │   ├── routes/
│   │   │   └── controllers/
│   │   ├── models/
│   │   ├── services/
│   │   ├── middleware/
│   │   └── config/
│   ├── package.json
│   └── server.js
├── database/
│   ├── migrations/
│   └── seeds/
├── docs/
│   ├── api.md
│   └── deployment.md
└── docker-compose.yml
```

---

## Setup & Installation

### Prerequisites

- Node.js (v18 or higher)
- Python (v3.9 or higher)
- PostgreSQL (v14 or higher)
- npm or yarn package manager
- Git

### Quick Start

**1. Clone the repository**

```bash
git clone https://github.com/caresphere/caresphere-wellness.git
cd caresphere-wellness
```

**2. Install frontend dependencies**

```bash
cd frontend
npm install
```

**3. Install backend dependencies**

```bash
cd ../backend
npm install
```

**4. Configure environment variables**

Create a `.env` file in the backend directory:

```env
PORT=5000
DATABASE_URL=postgresql://user:password@localhost:5432/caresphere
JWT_SECRET=your_jwt_secret
WHATSAPP_API_KEY=your_whatsapp_api_key
MPESA_CONSUMER_KEY=your_mpesa_consumer_key
MPESA_CONSUMER_SECRET=your_mpesa_consumer_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

**5. Set up the database**

```bash
# Create database
createdb caresphere

# Run migrations
npm run migrate

# Seed initial data
npm run seed
```

**6. Start the development servers**

```bash
# Backend (from /backend)
npm run dev

# Frontend (from /frontend)
npm start
```

**7. Access the application**

- Frontend: `http://localhost:3000`
- Backend API: `http://localhost:5000/api`
- API Documentation: `http://localhost:5000/api/docs`

---

## Deployment

### Production Build

```bash
cd frontend
npm run build
cd ../backend
npm run build
```

### Docker Deployment

```bash
docker-compose up -d
```

### AWS Deployment

1. Set up EC2 instance with Node.js and PostgreSQL
2. Configure S3 bucket for static asset storage
3. Deploy built frontend to S3 with CloudFront CDN
4. Deploy backend to EC2 with PM2 process manager
5. Configure Nginx as reverse proxy
6. Set up SSL certificate with Let's Encrypt

---

## API Endpoints

### Authentication

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/api/auth/register` | User registration |
| POST | `/api/auth/login` | User login |
| POST | `/api/auth/refresh` | Refresh JWT token |
| POST | `/api/auth/logout` | User logout |

### Health Assessments

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/assessments` | Get all assessments |
| POST | `/api/assessments` | Create new assessment |
| GET | `/api/assessments/:id` | Get assessment details |
| PUT | `/api/assessments/:id` | Update assessment |
| DELETE | `/api/assessments/:id` | Delete assessment |

### Care Coordination

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/appointments` | Get appointments |
| POST | `/api/appointments` | Schedule appointment |
| PUT | `/api/appointments/:id` | Update appointment |
| GET | `/api/referrals` | Get referrals |
| POST | `/api/referrals` | Create referral |

### E-Commerce

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/products` | Get all products |
| GET | `/api/products/:id` | Get product details |
| POST | `/api/cart` | Add to cart |
| GET | `/api/cart` | Get cart |
| POST | `/api/checkout` | Process checkout |

### Blog

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/posts` | Get blog posts |
| GET | `/api/posts/:id` | Get post details |
| POST | `/api/posts` | Create post |
| PUT | `/api/posts/:id` | Update post |
| GET | `/api/categories` | Get categories |

---

## Testing

```bash
# Run frontend tests
cd frontend
npm test

# Run backend tests
cd backend
npm test

# Run end-to-end tests
npm run test:e2e
```

---

## Performance Optimization

- Lazy loading of images and components
- Code splitting for reduced bundle size
- CDN integration for static assets
- Database query optimization with indexes
- Redis caching for frequently accessed data
- Compression middleware for API responses

---

## Future Roadmap

### Phase 1 (Q1 2025)
- Complete MVP launch
- Client dashboard development
- Telehealth integration
- Mobile app development (React Native)

### Phase 2 (Q2 2025)
- AI health assistant implementation
- Digital health records system
- Corporate wellness portal
- Prescription upload and management

### Phase 3 (Q3 2025)
- Preventive care analytics
- Membership subscriptions
- Family health plans
- Integration with national health systems

### Phase 4 (Q4 2025)
- Pan-African expansion
- Multi-language support
- Advanced health tracking
- Blockchain for health records

---

## Team

### Leadership

**Ephraim Amiani** - Founder & Clinical Lead
- Trained Clinical Officer
- Preventive health strategist
- Healthcare systems architect
- Risk-based care model expert

### Development Team

- Full Stack Engineers
- UI/UX Designers
- DevOps Engineers
- Quality Assurance Specialists
- Data Scientists

---

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Contribution Guidelines

- Follow the existing code style and formatting
- Write comprehensive tests for new features
- Update documentation accordingly
- Ensure all CI checks pass
- Use conventional commit messages

---

## License

This project is proprietary and confidential. Unauthorized copying, distribution, or use is strictly prohibited.

© 2025 CARESPHERE WELLNESS. All rights reserved.

---

## Contact

**CARESPHERE WELLNESS**

- **Location**: Westlands, Chiromo Lane, Medical Suites, 3rd Floor, Nairobi, Kenya
- **Phone**: +254 712 155 510
- **WhatsApp**: +254 712 155 510
- **Email**: caresphere@gmail.com
- **Website**: www.carespherewellness.co.ke

---

## Acknowledgments

- Kenya Medical Practitioners and Dentists Council (KMPDC)
- Office of the Data Protection Commissioner (ODPC)
- Healthcare partners and collaborators
- The open-source community

---

*Your Health. Professionally Managed.*
