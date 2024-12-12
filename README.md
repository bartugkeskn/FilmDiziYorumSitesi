# FilmDiziYorumSitesi-With-Asp.net

This project is a web platform where users can comment on TV series and movies, rate content, and interact with other users. It is developed using the ASP.NET MVC framework and features a modern web application architecture.

## Features

- **User Registration and Login System:**
  - Users can register and log in to the system.
  - User roles (admin, standard user) are supported.

- **Movie and TV Show Listing:**
  - All content is listed by categories.
  - Each content has a detail page displaying its description, image, and user comments.

- **Commenting and Rating:**
  - Users can leave comments and rate content out of 5.
  - Comments require admin approval.

- **Admin Panel:**
  - Administrators can add, edit, or delete content.
  - They can also approve and manage user comments.

## Technologies Used

- **Backend:**
  - ASP.NET
  - Entity Framework (Database First approach)
  - LINQ

- **Frontend:**
  - HTML5, CSS3, Bootstrap
  - JavaScript, jQuery

- **Database:**
  - Microsoft SQL Server

## Installation

To run the project, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/bartugkeskn/FilmDiziYorumSitesi-With-Asp.net.git
   ```

2. **Set Up the Database:**
   - Update the `appsettings.json` file with your SQL Server connection string.
   - Run the following command in the Package Manager Console to create the database:
     ```bash
     update-database
     ```

3. **Run the Project:**
   - Open the project in Visual Studio and run it using `IIS Express` or your preferred web server.

## Contribution

If you'd like to contribute to this project, follow these steps:

1. Fork this repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Description of the feature added"
   ```
4. Push your changes:
   ```bash
   git push origin feature-name
   ```
5. Create a pull request.

## License

This project is licensed under the MIT License. For more details, see the [LICENSE](LICENSE) file.

## Contact

If you have any questions or suggestions, feel free to contact me via the following channels:

- **GitHub:** [bartugkeskn](https://github.com/bartugkeskn)
- **Email:** bartukeskin1999@gmail.com

---

Thank you and happy coding!
