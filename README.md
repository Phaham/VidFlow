# VidFlow 🎬

**Angular Short Video Sharing Platform**

A sleek and modern video sharing platform built with Angular that empowers users to upload, share, and discover captivating short video clips and GIFs. Transform your creative moments into viral content with our intuitive, lightning-fast web application.

## Features

- 📹 **Upload & Share**: Upload short video clips and GIFs with ease
- 🎨 **Video Management**: Edit video details, manage your uploads
- 🔍 **Discover Content**: Browse and discover clips from other users
- 👤 **User Authentication**: Secure user registration and login system
- 📱 **Responsive Design**: Optimized for desktop and mobile viewing
- ⚡ **Fast Performance**: Built with modern web technologies for optimal speed

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn package manager
- Angular CLI

### Installation

1. Clone the repository
```bash
git clone <repository-url>
cd clips-master
```

2. Install dependencies
```bash
npm install
```

3. **Set up Firebase (Required)**
   - Go to [Firebase Console](https://console.firebase.google.com/)
   - Create a new project
   - Enable Authentication (Email/Password)
   - Enable Firestore Database 
   - Enable Storage
   - Get your Firebase config and update `src/environments/environment.ts`

4. Start the development server
```bash
ng serve
```

5. Open your browser and navigate to `http://localhost:4200/`

## Development

### Running the Development Server

```bash
ng serve
```
The application will automatically reload when you make changes to the source files.

### Building for Production

```bash
ng build --prod
```
Build artifacts will be stored in the `dist/` directory, ready for deployment.

### Running Tests

Execute unit tests:
```bash
ng test
```

## Technology Stack

- **Frontend**: Angular 14+, TypeScript, Tailwind CSS
- **Authentication**: Firebase Auth
- **Storage**: Firebase Storage
- **Database**: Firestore
- **Video Processing**: FFmpeg.js
- **Deployment**: Vercel/Firebase Hosting

## Project Structure

- `src/app/components/` - Reusable UI components
- `src/app/services/` - Business logic and API services
- `src/app/models/` - Data models and interfaces
- `src/app/user/` - User authentication and profile management
- `src/app/video/` - Video upload, editing, and management features

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---

Built with ❤️ using Angular CLI version 14.2.2
