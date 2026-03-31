# 256ROOTS' VOICE

A full-stack conservation platform connecting Uganda's wildlife heritage with global conservation efforts.

## 🌍 Features

- 🦁 **Wildlife Chronicle** - Species profiles with conservation status
- 🌍 **Climate Sync** - Real-time weather dashboards
- 🎙️ **Voices of the Wild** - Multimedia storytelling hub
- 📁 **File Storage** - Upload and manage wildlife photos, podcasts, documents
- 👥 **User Authentication** - Secure OAuth login
- 📊 **Conservation Impact** - Track environmental initiatives

## 🛠️ Tech Stack

- **Frontend**: React 19, TypeScript, Tailwind CSS 4
- **Backend**: Express.js, tRPC 11, Node.js
- **Database**: MySQL with Drizzle ORM
- **Storage**: S3 file storage with CDN
- **Testing**: Vitest (15 comprehensive tests)
- **Authentication**: Manus OAuth

## 📦 Project Structure

## 🚀 Getting Started

### Prerequisites
- Node.js 22+
- pnpm (or npm)
- MySQL database

### Installation

```bash
# Install dependencies
pnpm install

# Setup database
pnpm db:push

# Start development server
pnpm dev
DATABASE_URL=mysql://user:password@localhost:3306/256roots_voice
JWT_SECRET=your_jwt_secret_here
VITE_APP_ID=your_app_id
OAUTH_SERVER_URL=https://api.manus.im
VITE_OAUTH_PORTAL_URL=https://oauth.manus.im
BUILT_IN_FORGE_API_URL=https://api.manus.im
BUILT_IN_FORGE_API_KEY=your_api_key_here
