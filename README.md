# SIM Klinik - Clinical Management System

A comprehensive solution for managing clinical practices, patients, and appointments efficiently.

## Features

### 1. User Authentication
- Multi-role authentication system (admin, doctor, nurse, patient)
- Secure login and registration
- Role-based access control

### 2. Dashboard
- Overview of clinic activities
- Key metrics and statistics
- Recent patient visits
- Upcoming appointments

### 3. Patient Management
- Patient registration and records
- Medical history tracking
- Search and filter capabilities
- Electronic Health Records (EHR)

### 4. Appointment System
- Schedule management
- Appointment status tracking
- Doctor availability calendar
- Patient scheduling interface

### 5. Staff Management
- Doctor and staff profiles
- Specialization tracking
- Schedule management
- Contact information

### 6. SATUSEHAT Integration
- Connectivity with Indonesia's Healthcare Information System
- Secure credential management
- Data synchronization capabilities
- Compliance with healthcare standards

## Technology Stack

- **Frontend**: React with TypeScript
- **Backend**: Express.js
- **State Management**: TanStack Query (React Query)
- **UI Components**: shadcn/ui
- **Styling**: Tailwind CSS
- **Authentication**: Passport.js
- **Forms**: React Hook Form with Zod validation

## Getting Started

### Prerequisites
- Node.js >= 20
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone <repository-url>
cd sim-klinik
```

2. Install dependencies
```bash
npm install
```

3. Start the development server
```bash
npm run dev
```

The application will be available at `http://localhost:5000`

## User Roles

### Admin
- System configuration
- User management
- SATUSEHAT integration setup
- Access to all features

### Doctor
- View and manage appointments
- Access patient records
- Update medical records
- Set availability

### Nurse
- Patient registration
- Basic record management
- Appointment scheduling
- Patient coordination

### Patient
- View personal medical records
- Schedule appointments
- Update personal information
- View appointment history

## SATUSEHAT Integration

### Setup Requirements
- SATUSEHAT Client ID
- Client Secret
- Organization ID
- Valid healthcare provider credentials

### Configuration
1. Log in as an admin
2. Navigate to Settings > SATUSEHAT Integration
3. Enter the required credentials
4. Enable the integration

## Development

### Project Structure
```
sim-klinik/
├── client/           # Frontend React application
├── server/           # Backend Express server
├── shared/           # Shared types and schemas
└── public/           # Static assets
```

### Key Files
- `schema.ts`: Data models and validation
- `auth.ts`: Authentication logic
- `routes.ts`: API endpoints
- `storage.ts`: Data storage interface

### Development Guidelines
1. Follow TypeScript best practices
2. Use React Query for data fetching
3. Implement proper error handling
4. Maintain consistent code formatting
5. Write clear commit messages

## Security

- Password hashing using scrypt
- Session-based authentication
- Role-based access control
- Secure credential storage
- API route protection

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.
