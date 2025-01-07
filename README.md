# YelpCamp

YelpCamp is a cutting-edge full-stack web application where users can explore, review, and add campgrounds. Designed with modern technologies, it offers an interactive and seamless experience for camping enthusiasts to share their adventures and discover new destinations.

## Features

- **User Authentication**: Secure sign-up, log-in, and profile management.
- **Campground Management**: Create, edit, and delete campgrounds effortlessly.
- **Dynamic Reviews**: Engage with the community by leaving detailed reviews.
- **Interactive Map Integration**: Powered by Mapbox, view campgrounds with precision on an intuitive map interface.
- **Responsive Design**: Enjoy a fully optimized experience across all devices, from desktop to mobile.

## Tech Stack

YelpCamp leverages a robust and modern technology stack to deliver exceptional performance:

- **Backend**: Built with Node.js and Express.js for scalable and efficient server-side logic.
- **Frontend**: Developed using EJS and styled with Bootstrap for clean and responsive UI.
- **Database**: MongoDB with Mongoose for reliable and flexible data management.
- **Authentication**: Secured with Passport.js for streamlined user access control.
- **Mapping Services**: Mapbox API for visually rich and interactive maps.
- **Hosting**: Deployed on Heroku for reliable cloud hosting.

## Installation

Follow these steps to run YelpCamp locally:

1. Clone the repository:

   ```bash
   git clone https://github.com/yishayt2004/YelpCamp.git
   cd YelpCamp
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Set up environment variables:

   Create a `.env` file in the root directory with the following:

   ```env
   DATABASE_URL=<your-mongodb-connection-string>
   MAPBOX_TOKEN=<your-mapbox-access-token>
   SESSION_SECRET=<your-session-secret>
   ```

4. Seed the database (optional):

   ```bash
   node seeds/index.js
   ```

5. Start the application:

   ```bash
   node app.js
   ```

6. Open the app in your browser:

   ```
   http://localhost:3000
   ```

## Screenshots

## Screenshots

![Homepage Screenshot](assets/images/screemshot.jpg)
*Description: The beautifully designed homepage welcoming users to YelpCamp.*


## Contributing

We welcome contributions to YelpCamp! Whether it's fixing bugs, adding features, or improving documentation, feel free to open issues or submit pull requests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

### Contact

For questions, feedback, or collaboration opportunities, reach out to Yishay Tiram: [ishaylotiram@gmail.com](mailto:ishaylotiram@gmail.com).
