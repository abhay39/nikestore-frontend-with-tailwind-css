# Nike Store Project

![Nike Store](https://your-image-url.com/nike-store-screenshot.png)

This is a mobile-responsive Nike Store web application built using Next.js and Tailwind CSS. The project aims to showcase a simple e-commerce store where users can browse and purchase Nike products. It's designed to be a starting point for building your own online store or e-commerce project.

## Features

- Mobile-responsive design for a seamless shopping experience on all devices.
- Browse and search for Nike products.
- View detailed product information, including images, price, and description.
- Add products to the cart and update quantities.
- Calculate the total cost of items in the cart.
- Proceed to checkout and enter shipping and payment information.

## Technologies Used

- [Next.js](https://nextjs.org/): A React framework for building server-rendered React applications.
- [Tailwind CSS](https://tailwindcss.com/): A highly customizable, low-level CSS framework.
- [React](https://reactjs.org/): A JavaScript library for building user interfaces.
- [Redux](https://redux.js.org/): A state management library for React.
- [React Query](https://react-query.tanstack.com/): A data-fetching and state management library for React applications.
- [Firebase](https://firebase.google.com/): Used for authentication and real-time database storage.
- [Stripe](https://stripe.com/): Used for payment processing.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Node.js and npm installed on your machine.
- A Firebase account for authentication and database storage.
- A Stripe account for payment processing.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/abhay39/nikestore-frontend-with-tailwind-css.git
   cd nike-store
   ```

2. Install the dependencies:

   ```bash
   npm install
   ```

3. Set up Firebase:
   
   - Create a Firebase project on the [Firebase Console](https://console.firebase.google.com/).
   - Create a `.env.local` file in the project root and add your Firebase configuration:

     ```env
     NEXT_PUBLIC_FIREBASE_API_KEY=your-api-key
     NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your-auth-domain
     NEXT_PUBLIC_FIREBASE_PROJECT_ID=your-project-id
     NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your-storage-bucket
     NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your-messaging-sender-id
     NEXT_PUBLIC_FIREBASE_APP_ID=your-app-id
     ```

4. Set up Stripe:

   - Create a Stripe account on the [Stripe Dashboard](https://dashboard.stripe.com/).
   - Add your Stripe API key to the `.env.local` file:

     ```env
     STRIPE_SECRET_KEY=your-stripe-secret-key
     ```

5. Start the development server:

   ```bash
   npm run dev
   ```

6. Open your browser and go to [http://localhost:3000](http://localhost:3000) to see the app in action.

## Deployment

To deploy this project to a production environment, you can follow the deployment instructions for Next.js applications. Popular options include Vercel, Netlify, and hosting on your own server.

## Contributing

If you'd like to contribute to this project, please follow our [contributing guidelines](CONTRIBUTING.md).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Special thanks to the Next.js and Tailwind CSS communities for their amazing tools and resources.
- Inspiration for this project comes from the Nike online store.

## Contact

If you have any questions or want to reach out to the project maintainers, you can contact us at abhayguptaak39@gmail.com.

Enjoy building your Nike Store project! Happy coding! 👟🛒🚀
