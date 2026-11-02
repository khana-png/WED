# Dr Johnjohnson Dental Practice Website

A responsive website project for **Dr Johnjohnson Dental Practice**, using the slogan **“Your Smile, Our Priority.”** The website is intended to help visitors learn about the practice, explore dental services, read patient feedback, contact the practice and request an appointment.

## Project objectives

- Present the practice in a professional and welcoming way.
- Provide clear navigation between the website pages.
- Display practice information, mission, vision and dental services.
- Allow visitors to prepare an appointment request.
- Present client reviews in a clear card-based layout.
- Support desktop, tablet and mobile screen sizes.
- Provide a foundation for a secure dentist portal to review and manage appointment requests.

## Technologies

- **HTML5** – page structure and content.
- **CSS3** – layout, visual styling, responsive design and transitions.
- **JavaScript** – client-side interactions and form validation.

No build tools are required for the basic static website.

## Main pages and features

| Page / feature | Description |
| --- | --- |
| Home | Practice introduction and links to important actions. |
| About | Practice story, mission and vision. |
| Services | Information about available dental treatments. |
| Appointments | Appointment request form for patient details, date, time and treatment. |
| Contact | Contact information and enquiry route. |
| Client Reviews | Review cards, star ratings, images and service labels. |
| Dentist portal (development enhancement) | Intended protected sign-in area for authorised dentists to view and accept or decline bookings. |

## Suggested project structure

Keep the files organised in a structure similar to this. Your actual filenames may differ; update the links and this README to match the final project folder.

```text
Dr-Johnjohnson-Dental-Practice/
├── index.html
├── about.html
├── services.html
├── appointment.html
├── contact.html
├── clientsReviews.html
├── dentist-login.html              # if implemented
├── dentist-dashboard.html          # if implemented
├── css/
│   ├── style.css
│   └── appointment.css              # if used
├── js/
│   ├── script.js
│   ├── appointment.js                # if separated
│   └── dentist-auth.js               # if implemented
├── images/
│   └── (website images and logo)
└── README.md
```

## How to run the website

1. Download or clone the project repository.
2. Extract the project folder if it was downloaded as a ZIP file.
3. Open the project folder in Visual Studio Code or another code editor.
4. Check that the CSS, JavaScript and image paths in each HTML file match the folder structure.
5. Open `index.html` in a web browser, or use the VS Code **Live Server** extension.
6. Navigate through each page and test the forms and interactive features.

For example, with Git installed:

```bash
git clone YOUR_REPOSITORY_URL
cd Dr-Johnjohnson-Dental-Practice
```

Replace `YOUR_REPOSITORY_URL` with the actual GitHub repository URL.

## Appointment form

The appointment form is intended to collect the patient's name, preferred appointment date, time and treatment. Client-side validation can check that required fields are completed before the request is submitted.

**Important:** A static HTML/CSS/JavaScript website does not automatically save appointment requests to a central database or send them to a dentist. If the current project uses browser-only sample data, requests may not be shared across devices or users. Connect the form to a backend or trusted database service before using it for real bookings.

## Dentist sign-in and appointment management

The planned dentist workflow is:

1. An authorised dentist signs in.
2. The dentist opens a protected appointment dashboard.
3. The dashboard displays incoming appointment requests.
4. The dentist accepts or declines a request.
5. The appointment status is updated and shown to the appropriate user.

A production version must use secure server-side authentication, password hashing, role-based access control, protected sessions and database security rules. Do not store real passwords in plain text or use `localStorage` as the only security mechanism. Do not publish real patient information in a public repository.

## Testing before submission

- [ ] All navigation links open the correct pages.
- [ ] All pages load without missing images or stylesheets.
- [ ] Appointment form required fields are validated.
- [ ] Appointment date and time rules work as expected.
- [ ] Forms display understandable success and error messages.
- [ ] Review cards and interactive elements work on desktop and mobile.
- [ ] The website is usable with keyboard navigation.
- [ ] Dentist login and appointment permissions are tested, if implemented.
- [ ] No real patient data, passwords, API keys or private configuration files are committed to GitHub.

## Deployment

The website can be published using a static hosting service such as **GitHub Pages** or **Netlify** for the public-facing pages. A backend service is required for secure authentication and shared appointment management. Configure and test the backend separately before enabling real patient bookings.

## Privacy and content notes

Use only verified practice contact information. Obtain permission before publishing identifiable patient names, photographs or testimonials. Use sample data for demonstrations and coursework screenshots.

## Project documentation

The accompanying Word report, `Dr_Johnjohnson_Website_Improvement_Report_Parts_1_to_3.docx`, documents project planning, website design and development, interactive features, testing and recommended improvements.

## Author / submission details

- Project: Dr Johnjohnson Dental Practice Website
- Repository: Add your GitHub repository URL
- Live website: Add your deployed website URL
- Submission date: Add the date required by your lecturer
