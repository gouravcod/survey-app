# Survey App

A standalone **Ionic Angular** application for a multi-step survey. Users log in, enter personal details, answer questions, review, and submit responses. It features secure authentication, form validation, data persistence, and a reset mechanism, tested with **Jasmine** and **Karma**.

---

## 📦 Features

- 🔐 **Secure Login**: Login required; redirects to `/login` with a warning toast for unauthorized access.
- 📝 **Multi-Step Survey**:
  - Enter `name`, `email`, `age` with validation.
  - Answer survey questions.
  - Review and submit responses.
- ✅ **Form Validation**: Enforces required fields, valid email format, and `age ≥ 18`.
- 🚀 **Dynamic Navigation**: “Next” button enables only for valid input.
- 💾 **Data Persistence**: Saves form data across steps using `SurveyService`.
- 🔄 **Form Reset**: Clears form after submission/restart, fixing persistence issues.
- 🎨 **UI Design**: Centered `ion-card` with animations (e.g., shake on errors).
- 🧪 **Unit Testing**: 10+ tests for validation, navigation, and authentication.

---

## 🛠️ Technologies Used

- [Ionic Framework](https://ionicframework.com/)
- [Angular](https://angular.io/)
- [RxJS - Subject](https://rxjs.dev/)
- [Reactive Forms](https://angular.io/guide/reactive-forms)
- Jasmine + Karma (Unit Testing)

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/survey-app.git
cd survey-app
