<a id="readme-top"></a>

<!-- HEADER -->
<div align="center">
  <h3 align="center">Industry Hub</h3>
  <p align="center">
    Cross-platform mobile application for managing the maintenance of an industrial workplace.
  </p>
</div>

<!-- ABOUT THE PROJECT -->
## About The Project
This application is designed to streamline the maintenance and repair processes in a workplace, specifically developed for a client in the industrial sector.<br>

It allows users to manage and track device maintenance tasks, occurrence of faults and relevant repair activities. The app provides information about every device on a workplace, displaying the status of each one and its components in real-time.<br>

The purpose of this application is to provide workers with a clear overview of the entire workplace’s status and to create plans and recommendations for necessary tasks. The application was both automated and user-tested.

## Key features

### Authentication
- App uses Firebase Auth for user authentication via email and password.<br>
- A password reset option and automatic login are available to users.<br>

### Navigation
- Navigation in the app is handled using a custom navigation bar. It includes a settings button for profile management and logout, and a home button for quick access to the main screen.<br>
- Home screen serves as a central hub with icon-based buttons linking to key sections.

### Devices
- Device page lists all available devices with corresponding images and key status information.<br>
- Users can access a detailed view with maintenance schedules and current fault counts via a "DETAIL" button.<br>
- From the detailed view, users can navigate to maintenance, faults, and repair functionalities of that particular device.

### Components
- Some devices require maintenance as a whole, but most consist of multiple parts needing individual care.<br>
- Each device has a collection of its parts, each with unique properties and maintenance intervals.<br>
- The maintenance interval defines the number of days within which a part requires at least one maintenance action.<br>
- The parts list displays each component of a selected device, showing the last maintenance date and the next required maintenance deadline.

### Maintenance Management
- Maintenance management is the core of this application, with a goal to provide overview of all maintenance processes.<br>
- The maintenance record page displays past actions on particular part with information on date, description, and the worker responsible.<br>
- On the parts page, a new maintenance record can be created or an existing one can be edited/deleted.<br>

### Faults and Repairs
- Faults are an unfortunate but common part of any manufacturing environment. This app allows users to record them with the goal of the fastest possible repair.<br>
- Once a fault is resolved, it can be marked as "repaired," and the app also tracks repair records.<br>
- All these faults and repairs records can be found in the records section, along with detailed information, their status and photo documentation.<br>

### Other Functionalities
The app provides additional pages that facilitate maintenance operations:

- **Workplace**: Displays a floor plan of the workplace with devices marked in different colors based on their status, such as "Normal" "Maintenance Needed" or "Active Fault". Clicking on a device redirects the user to its detailed page.<br>
- **Plan**: Shows a table of upcoming maintenance tasks, sorted by due date. The idea behind this page is to have all records of faults in one place, giving the worker an overview of everything that needs repair. Users can click on a task to navigate directly to the device page and record the maintenance once completed.<br>

### Database
- In this app, **Firestore** is used to store the data.<br>
- In the database, there are stored information about every device on a workplace, including details such as the full name, year of manufacture, photo documentation, etc.<br>
- For each device, we store information about its faults and repairs. Additionally, details about individual parts of the device are also stored.<br>
- Parts are the main focus of maintenance, so for each part, maintenance records are kept.

<br>

<!-- TOOLS -->
### Built With  

* [![Flutter][Flutter.com]][Flutter-url]
* [![Dart][Dart.com]][Dart-url]  
* [![Firebase][Firebase.com]][Firebase-url]  

<!-- LINKS -->  
[Flutter.com]: https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white  
[Flutter-url]: https://flutter.dev  
[Firebase.com]: https://img.shields.io/badge/Firebase-FFCB2F?style=for-the-badge&logo=firebase&logoColor=black  
[Firebase-url]: https://firebase.google.com  
[Dart.com]: https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white  
[Dart-url]: https://dart.dev  

<br>

### Created  
2024

<p align="right">(<a href="#readme-top">back to top</a>)</p>
