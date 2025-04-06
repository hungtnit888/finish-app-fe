# Finish App Frontend

A modern Vue.js frontend application for the Finish App project.

## Tech Stack

- Vue 3
- TypeScript
- Vite
- Pinia (State Management)
- Vue Router
- Tailwind CSS
- Axios
- Jest (Testing)
- ESLint + Prettier
- Husky (Git Hooks)

## Prerequisites

- Node.js 18+
- npm 9+
- Git

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/your-username/finish-app-fe.git
cd finish-app-fe
```

2. Install dependencies:
```bash
npm install
```

3. Create environment file:
```bash
cp .env.example .env
```

4. Start development server:
```bash
npm run dev
```

## Project Structure

```
src/
├── assets/          # Static assets
├── components/      # Reusable components
├── composables/     # Vue composables
├── layouts/         # Layout components
├── router/          # Vue Router configuration
├── services/        # API services
├── stores/          # Pinia stores
├── types/           # TypeScript types
├── utils/           # Utility functions
└── views/           # Page components
```

## Development

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run test` - Run tests
- `npm run lint` - Run linter
- `npm run format` - Format code

## API Integration

The frontend integrates with the following backend APIs:

- Authentication: `/api/v1/auth/*`
- User Management: `/api/v1/users/*`
- Admin Functions: `/api/v1/admin/*`
- Public Access: `/api/v1/public/*`

## Environment Variables

- `VITE_API_BASE_URL` - Base URL for API requests
- `VITE_APP_TITLE` - Application title
- `VITE_APP_DESCRIPTION` - Application description

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. 