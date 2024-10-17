Overview
The Contract Monthly Claim System (CMCS) is a web-based application built with ASP.NET MVC, designed to streamline the process of submitting, reviewing, and approving monthly claims by Independent Contractor (IC) lecturers. The system allows lecturers to submit their claims, upload supporting documents, and track the status of their submissions. Programme Coordinators and Academic Managers are provided with tools to efficiently review, verify, and approve the claims.

Key Features
Claim Submission: Lecturers can submit their monthly claims with details such as hours worked and hourly rates.
Document Upload: Supporting documents can be uploaded alongside claims.
Verification and Approval: Programme Coordinators and Academic Managers can review and approve claims.
Claim Status Tracking: Lecturers can track the progress of their claims for full transparency.
User Role Management: Different roles (Lecturers, Programme Coordinators, Academic Managers) offer tailored functionality.
Technologies Used
ASP.NET Core MVC
C#
Entity Framework Core
SQL Server (database)
HTML, CSS, Bootstrap (front-end)
Azure (cloud-based file storage)
Installation and Setup
To set up the project:

Clone the repository:

bash
Copy code
git clone <repository-url>
Open the project in Visual Studio.

Restore NuGet packages:

bash
dotnet restore
Update the connection string in appsettings.json to your SQL Server instance.

Apply database migrations:

bash
dotnet ef database update
Run the application:

bash
dotnet run
Usage
Lecturers can log in to submit claims and upload documents.
Programme Coordinators and Academic Managers can log in to review and approve claims.
Contribution
Contributions are encouraged! Fork the repository and submit pull requests.

License
This project is licensed under the MIT License.
