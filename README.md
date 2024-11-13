# FabricFit
FabricFit is an Android app designed to empower tailors in the digital age. Featuring appointment scheduling, digital catalogs, measurement recording, order tracking, payment processing, and customer engagement tools, it leverages XML, JSON, Java, JS, and Firebase to streamline tailoring processes and enhance customer experiences.

# FabricFit - Android Tailoring App
### Introduction

FabricFit is a mobile application tailored to simplify the process of ordering custom garments and streamline communication between customers and tailors. With FabricFit, users can browse fabrics, submit measurements, and track orders all in one convenient app.FabricFit is an innovative Android tailoring app that redefines the tailoring experience for Admins, Customers, and Tailors. Admins manage fabric catalogs and track orders; Customers can place orders, provide measurements, and make secure payments; Tailors manage orders and appointments for streamlined operations. It’s efficient, user-friendly, and highly accessible.

### Features

- Intuitive online ordering with an easy-to-use interface.
- Flexible payment options including online payment and cash on delivery.
- Real-time order tracking for customers, tailors, and admins.
- Order and appointment management for improved workflow.
- Admin panel to manage fabrics, tailor profiles, and customer orders.

### Screenshots

- Home Page
- Fabric Catalog
- Order Tracking
- Admin Dashboard

### Installation

1. **Install Android Studio**: Android Studio provides the IDE needed for the project.
2. **Firebase Setup**:
   - Create a Firebase project and add an Android app.
   - Download the `google-services.json` file and place it in the `app` directory.
3. **Run the Application**:
   - Open the project in Android Studio.
   - Sync with Gradle and run the app on an emulator or Android device.

### Usage

- **Admin**: Log in to manage fabric catalogs, view sales reports, and oversee orders.
- **Customer**: Register, browse fabric catalogs, submit measurements, place orders, and track order status.
- **Tailor**: Register, manage orders, view customer measurements, and schedule appointments.

### Project Structure

```
FabricFit/
├── app/
│   ├── src/
│   │   ├── main/
│   │   ├── java/
│   │   ├── res/
│   ├── google-services.json
├── docs/
│   └── Documentation.pdf
├── README.md
└── LICENSE
```

### Technologies Used

- **Frontend**: XML for UI layout
- **Backend**: Java
- **Database**: Firebase Realtime Database
- **Development Environment**: Android Studio

### Database Schema

The Firebase database stores customer profiles, order records, fabric catalogs, and tailor information. Refer to the [Documentation.pdf](docs/Documentation.pdf) for detailed diagrams and the data structure.

### Future Enhancements

- **Tailor Ratings**: Allow customers to rate and review tailors for improved service transparency.
- **Advanced Fabric Visualization**: Provide realistic fabric previews using advanced imaging.
- **Push Notifications**: Send real-time updates on order progress.
- **Customer Loyalty Program**: Reward customers for repeat orders and referrals.

### Contributing

1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b feature-name`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a Pull Request.

### License

This project is licensed under the MIT License. See the `LICENSE` file for details.
