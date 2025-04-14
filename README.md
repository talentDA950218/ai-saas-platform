# AI-SaaS-Platform 

![Playground](/public/showcase/playground.PNG)

## Showcase

| ![Sign In](/public/showcase/signIn.PNG) | ![Sign Up](/public/showcase/singUp.PNG) |
|:---:|:---:|
| Sign In Page | Sign Up Page |

| ![Light Theme](/public/showcase/lightTheme.PNG) | ![Dark Theme](/public/showcase/darkTheme.PNG) |
|:---:|:---:|
| Light Theme | Dark Theme |

## Tech Stack

### Basic Version
- Next.js v14 App Router with JavaScript
- Next Auth
- Redux Toolkit
- Sass
- Styled Components
- Bootstrap
- React Libraries:
  - react-scroll
  - react-select
  - react-slick
  - react-tooltip

### Advanced Version
- Next.js v14 App Router with TypeScript
- Next Auth
- Redux Toolkit
- Sass
- Styled Components
- Advanced State Management
- Advanced Component Architecture

## Version Comparison

| Feature | Basic Version | Advanced Version |
|---------|--------------|------------------|
| Language | JavaScript | TypeScript |
| Auth | Next Auth with Google & Facebook OAuth | Next Auth with Google & Facebook OAuth |
| State Management | Redux Toolkit | Redux Toolkit with advanced patterns |
| UI Framework | Bootstrap, Sass, Styled Components | Bootstrap, Sass, Styled Components |
| Payment Integration | ❌ | ✅ Stripe & PayPal integration |
| Database Integration | ❌ | ✅ Prisma ORM with PostgreSQL |
| Deployment | Manual deployment | ✅ CI/CD pipeline with GitHub Actions |
| AI Models | OpenAI only | ✅ Multi-model support (OpenAI, Google Gemini, Anthropic) |
| Open Source Models | ❌ | ✅ Hugging Face and Ollama integration |
| Caching | Basic caching | ✅ Advanced caching strategies |
| Testing | ❌ | ✅ Jest and React Testing Library |
| Analytics | ❌ | ✅ Integration with Vercel Analytics |
| Performance Monitoring | ❌ | ✅ Real-time monitoring and error tracking |
| Internationalization | ❌ | ✅ Multi-language support |
| SEO | Basic SEO | ✅ Advanced SEO with structured data |
| API Documentation | ❌ | ✅ Swagger/OpenAPI docs |

## Features

### Authentication
- Google & Facebook OAuth
- JWT Authentication
- Secure Session Management

### AI Integration
- OpenAI Integration
- Image Generation
- Code Generation (Advanced)
- Custom LLM Providers (Advanced)
- Google Gemini Support (Advanced)
- Vercel AI SDK Implementation (Advanced)
- Llama Index Implementation (Advanced)
- Interactive AI Playground

### User Experience
- Responsive Design
- Dark/Light Theme Toggle
- Interactive UI Components
- Real-time Feedback

## Folder Structure

```
aiwave-nextjs-app/
├── app/                # Next.js App Router
├── components/         # Reusable UI components
├── context/            # React Context providers
├── data/               # Static data and configurations
├── provider/           # Service providers
├── public/             # Static assets
│   └── showcase/       # Application screenshots
├── store/              # Redux store configuration
├── .env                # Environment variables
├── jsconfig.json       # JavaScript configuration
├── next.config.mjs     # Next.js configuration
└── package.json        # Project dependencies
```

## Getting Started

First, install the dependencies:

```bash
npm install
# or
yarn install
# or
pnpm install
```

Then, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the application.

## Environment Setup

Create a `.env.local` file in the root directory with the following variables:

```
NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_SECRET=your_nextauth_secret

# OAuth Providers
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
FACEBOOK_CLIENT_ID=your_facebook_client_id
FACEBOOK_CLIENT_SECRET=your_facebook_client_secret

# AI Providers
OPENAI_API_KEY=your_openai_api_key
GEMINI_API_KEY=your_gemini_api_key
```

## Deployment

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new) from the creators of Next.js.

Check out the [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

## Author

- **Name**: John Zulhelmi
- **Email**: john.zulhelmi@ulex.ai
- **Website**: [talent.dev](https://john-zulhelmi.vercel.app)

### Connect with the Author

- **GitHub**: [github.com/talentDA950218](https://github.com/talentDA950218)
- **LinkedIn**: [/in/john-zulhelmi](https://www.linkedin.com/in/john-zulhelmi-222b4a337)
- **Telegram**: [@JohnDAT0218](https://t.me/JohnDAT0218)

## License

This project is licensed under the MIT License - see below for details:

```
MIT License

Copyright (c) 2023 AIWave

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
