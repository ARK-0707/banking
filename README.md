![BANKING PLATFORM](https://github.com/user-attachments/assets/3a2d601d-f3d3-4a90-829f-b813acd79ea9)

# Horizon Banking Platform

Welcome to the **Horizon Banking App**, a modern solution for seamless banking and financial management. Built with cutting-edge technologies, our website offers a secure and user-friendly platform to manage your finances, connect with your banks, and transfer funds with ease.


## 🌐 Website

Explore the live app: [Banking App](https://banking-livid-alpha.vercel.app/)

## 🚀 Features

1. **User Authentication**: Secure sign-in and sign-up features to protect user data and privacy.
2. **Bank Connectivity**: Easily connect multiple bank accounts using Plaid to manage your finances in one place.
3. **Fund Transfers**: Transfer funds effortlessly using a shareable ID, simplifying transactions across different accounts.
4. **Real-time Error Monitoring**: Integrated with Sentry for robust error tracking and logging to ensure a smooth user experience.
5. **Modern UI**: Built with shadcn for a sleek and intuitive user interface, providing a seamless experience on all devices.

## 🛠️ Tech Stack

- **Next.js**: A powerful React framework for server-side rendering and generating static websites, enabling fast and dynamic web applications.
- **shadcn**: A utility-first CSS framework that provides a minimal and customizable style, enhancing the app's design and user experience.
- **Sentry**: Integrated for error monitoring and performance tracking, ensuring a smooth and reliable user experience.
- **Dwolla**: A robust API for handling secure and efficient bank transfers.
- **Plaid**: A trusted service for securely connecting your bank accounts and retrieving financial data.
- **Appwrite**: An open-source backend-as-a-service platform that simplifies backend development with integrated authentication, database, storage, and functions.

## 📸 Screenshots

Here are some glimpses of our app:

- **Landing Page**: ![image](https://github.com/user-attachments/assets/e73c3f5a-01bb-4af8-bcf2-1cf12e31fab8)
- **Sign-Up Page**: ![image](https://github.com/user-attachments/assets/8546c10c-9583-431f-bd6a-f73b934fd509)
- **My Banks Page**: ![image](https://github.com/user-attachments/assets/89b86f1c-2f4f-498f-a4d8-fcc08c19f82a)
- **Fund Transfer Page**: ![image](https://github.com/user-attachments/assets/2169acde-9e19-44b0-9c8b-42b612dc8dbf)
- **Transaction History Page**: ![image](https://github.com/user-attachments/assets/d607ecc0-8af6-4921-8377-8388747b7bf4)
- **Connect Bank Page**: ![image](https://github.com/user-attachments/assets/18c35e5e-417a-4455-a4a8-3badb6dd152d)

## 📖 Getting Started

To run this project online, follow these steps:
1. **Go to the Website**:
   [Banking App](https://banking-livid-alpha.vercel.app/)

2. **Sign-Up as a New User**:
   Fill the details in the sign-up form. Remember to put the correct email and password as well as city and state according to the US's states and cities. You can put anything in the other fields.

3. **Connect Bank**:
   After the filling of the sign-up form. Click on the *Connect bank* button to connect your bank and for the plaid & dwolla username & password you can use:
   ```bash
   username: user_good
   password: pass_good
   ```

4. **Dashboard**:
   After you connect your bank and agree to all the policies. you will be redirected to the Dashboard of the website where you can see your connected banks. Some fake transactions fetched from the Dwolla Sandbox.

5. **Start Transfer Funds**:
   You now start transferring your funds but remember to have shareable Id of the reciever and also this is a sandbox payment so it will takes 5-6 days to show the transaction success but it will show that the transfer is in the process.

To run this project locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/banking-app.git
   cd banking-app
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Environment Variables**: Create a `.env.local` file and add your environment variables. Refer to `.env.example` for required variables.

4. **Run the Development Server**:
   ```bash
   npm run dev
   ```

   The app will be running on [http://localhost:3000](http://localhost:3000).

## 🪪 Important 

All the transfer of money and data showing in the website is not real rather it is generated from the dwolla sandbox to only show how these kinds of bank transactions work. The money transferred in the website is not real.

## 🤝 Contributing

We welcome contributions! Please see our [CONTRIBUTING.md](https://github.com/your-username/banking-app/blob/main/CONTRIBUTING.md) for guidelines.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/your-username/banking-app/blob/main/LICENSE) file for details.
