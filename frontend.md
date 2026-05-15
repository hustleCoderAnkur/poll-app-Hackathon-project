src/
├── api/
│   ├── axios.js
│   ├── auth.api.js
│   ├── poll.api.js
│   ├── question.api.js
│   └── response.api.js
│
├── components/
│   ├── common/
│   │   ├── Navbar.jsx
│   │   ├── Loader.jsx
│   │   ├── Button.jsx
│   │   ├── Input.jsx
│   │   └── ProtectedRoute.jsx
│   │
│   ├── poll/
│   │   ├── PollCard.jsx
│   │   ├── PollForm.jsx
│   │   ├── QuestionForm.jsx
│   │   ├── OptionInput.jsx
│   │   ├── PollAnalytics.jsx
│   │   └── PollResults.jsx
│   │
│   └── response/
│       ├── ResponseForm.jsx
│       └── ResponseQuestion.jsx
│
├── context/
│   └── AuthContext.jsx
│
├── hooks/
│   ├── useAuth.js
│   ├── useSocket.js
│   └── usePoll.js
│
├── layouts/
│   ├── MainLayout.jsx
│   └── DashboardLayout.jsx
│
├── pages/
│   ├── auth/
│   │   ├── LoginPage.jsx
│   │   └── RegisterPage.jsx
│   │
│   ├── dashboard/
│   │   ├── DashboardPage.jsx
│   │   ├── CreatePollPage.jsx
│   │   ├── EditPollPage.jsx
│   │   └── AnalyticsPage.jsx
│   │
│   ├── public/
│   │   ├── PollPage.jsx
│   │   └── ResultPage.jsx
│   │
│   ├── HomePage.jsx
│   └── NotFoundPage.jsx
│
├── routes/
│   └── AppRoutes.jsx
│
├── sockets/
│   └── socket.js
│
├── utils/
│   ├── formatDate.js
│   ├── constants.js
│   └── validators.js
│
├── App.jsx
├── main.jsx
└── index.css



