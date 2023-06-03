# Facial-Recognition-Website


# Hospital Management System with Face Recognition

This project is a Hospital Management System that incorporates face recognition technology for authentication. It is built using Python, Flask web framework, OpenCV for face detection and recognition (using Haar cascades), PCA algorithm for feature extraction, `numpy` for array manipulation, Jinja2 template engine for rendering dynamic web pages, and PHP for server-side scripting with XAMPP server.

## Features

- User Registration: Users can register with the system by providing their personal details and uploading their profile picture.
- Face Enrollment: Registered users can enroll their faces by capturing multiple images for training the face recognition model.
- Face Recognition: The system uses Haar cascades for face detection, PCA algorithm for feature extraction, and OpenCV for face recognition to authenticate users based on their enrolled faces.
- Appointment Management: Patients can schedule appointments with doctors and view their upcoming appointments.
- Doctor Management: Doctors can manage their schedules, view appointments, and update patient records.
- Admin Panel: An admin panel is provided for managing doctors, patients, appointments, and system settings.

## Installation

1. Clone the repository:

```
git clone https://github.com/YashGupta4/Facial-Recognition-Website.git
```

2. Change into the project directory:

```
cd hms
```

3. Install and set up XAMPP:

   - Download and install XAMPP from the [official website](https://www.apachefriends.org/index.html).
   - Start the XAMPP control panel and start the Apache and MySQL services.

4. Move the project directory to the XAMPP `htdocs` folder:

   - On Windows: `C:\xampp\htdocs`
   - On macOS: `/Applications/XAMPP/htdocs`
   - On Linux: `/opt/lampp/htdocs`

5. Configure the database:

   - Import the provided SQL file (`database.sql`) into the MySQL database using phpMyAdmin or any other MySQL management tool.

6. Start the XAMPP server:

   - Open the XAMPP control panel and start the Apache and MySQL services.

7. Access the application in your browser at `http://localhost/hospital`.

## Usage

- Open the application in your browser.
- Register a new user account and upload a profile picture.
- Enroll your face by capturing multiple images from different angles.
- Use the face recognition feature to authenticate and access different sections of the system.
- Schedule appointments as a patient or manage appointments as a doctor.
- Explore other features and functionalities of the hospital management system.

## Contributing

If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and push the branch to your fork.
4. Submit a pull request describing your changes.

## License

This project is licensed under the [MIT License](LICENSE).

## Credits

- [Flask](https://flask.palletsprojects.com/)
- [OpenCV (with Haar cascades)](https://opencv.org/)
- [PCA Algorithm](https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.PCA.html)
- [NumPy](https://numpy.org/)
- [Jinja2 Template Engine](https://jinja.palletsprojects.com/)
- [PHP](https://www.php.net/)
- [XAMPP](https://www.apachefriends.org/index.html)

## Contact

For any questions or inquiries, please contact the project maintainer at info.guptayash@gmail.com

Feel free to update the information and
