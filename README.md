<p align="center">
  <img src="https://res.cloudinary.com/dyg5rtwwe/image/upload/v1733753082/rhwrs4hfyeifxivof3oy.png" alt="FontFound Mobile App">
</p>

<h1 align="center">FontFound</h1>

Fontfound is a mobile app designed to empower designers by instantly identifying fonts captured through a real-time camera, streamlining their creative process.

---

## Team Member C242-PS319		
<div align="center">

| Bangkit ID |             Name             |   Learning Path    |           Campus              |
|:----------:|:----------------------------:|:------------------:|:-----------------------------:|
|M001B4KY1753| Haykal Maulana Rulian        | Machine Learning   | Institut Pertanian Bogor      |
|M012B4KX1185| Dora Leonny Giselle Tambunan | Machine Learning   | Universitas Telkom            |
|M211B4KY2625| Muhammad Chaerul Anwar       | Machine Learning   | Universitas Indraprasta PGRI  |
|C370B4KY2684| Muhammad Adithya Pratama     | Cloud Computing    | STMIK IKMI Cirebon            |
|C156B4KY3753| Reski Junaidi Shalat         | Cloud Computing    | Sekolah Tinggi Teknologi TNF  |
|A247B4KY3019| Muhammad Raka Azwar          | Mobile Development | Universitas Lambung Mangkurat |
|A290B4KY0964| Daffa Fathan Romadhan        | Mobile Development | Universitas Pancasila         |

</div>

# Machine Learning
FontFound has built a model with TensorFlow Lite and TensorFlow. Js, used a data pipeline to serve the model, and preprocessed the data using Missing Values Imputation.

This directory includes a few sample datasets to get you started.

*   `california_housing_data*.csv` is California housing data from the 1990 US
    Census; more information is available at:
    https://docs.google.com/document/d/e/2PACX-1vRhYtsvc5eOR2FWNCwaBiKL6suIOrxJig8LcSBbmCbyYsayia_DvPOOBlXZ4CAlQ5nlDD8kTaIDRwrN/pub

*   `mnist_*.csv` is a small sample of the
    [MNIST database](https://en.wikipedia.org/wiki/MNIST_database), which is
    described at: http://yann.lecun.com/exdb/mnist/

*   `anscombe.json` contains a copy of
    [Anscombe's quartet](https://en.wikipedia.org/wiki/Anscombe%27s_quartet); it
    was originally described in

    Anscombe, F. J. (1973). 'Graphs in Statistical Analysis'. American
    Statistician. 27 (1): 17-21. JSTOR 2682899.

    and our copy was prepared by the
    [vega_datasets library](https://github.com/altair-viz/vega_datasets/blob/4f67bdaad10f45e3549984e17e1b3088c731503d/vega_datasets/_data/anscombe.json).

# Cloud Computing
## Features

- **NestJS Framework**: Modular and efficient API architecture.
- **Prisma ORM**: Powerful database interaction with schema-based type safety.
- **Docker Support**: Consistent and portable containerized deployments.
- **GitHub Actions**: Streamlined CI/CD for automated testing and deployment.
- **Google Cloud Run**: Serverless application hosting with scalable infrastructure.

---

## Prerequisites

To set up the project locally or for deployment, ensure the following tools are installed:

1. **Node.js** (v16 or higher)  
   - [Download Node.js](https://nodejs.org/)
   
2. **Docker**  
   - [Install Docker](https://www.docker.com/get-started)
   
3. **Google Cloud SDK**  
   - [Install Google Cloud SDK](https://cloud.google.com/sdk/docs/install)
   
4. **Git**  
   - [Install Git](https://git-scm.com/)

---

## Environment Variables

To configure the project, create a `.env` file in the root directory. Add the following environment variables:

```env
# Database connection URL
DATABASE_URL=your_database_connection_url

# Google Cloud Project credentials
PROJECT_ID=your_google_cloud_project_id
PRIVATE_KEY="your_google_cloud_service_account_private_key"
CLIENT_EMAIL=your_google_cloud_service_account_email

# Google Cloud Storage
STORAGE_MEDIA_BUCKET=your_google_cloud_storage_bucket_name
```

---

## Local Development
1. Clone the Repository
```bash
git clone https://github.com/your-username/fontfound-api.git
cd fontfound-api
```

2. Install Dependencies
```bash
npm install
```

3. Run Database Migrations
```bash
npx prisma migrate dev
```

4. Start the Development Server
```bash
npm run start:dev
```

5. Access the API Open your browser or API client at:
```bash
http://localhost:<your port>
```

---

# Mobile Development

## Featured Tehcnologies

**Kotlin**: A modern, concise, and safe programming language that's easy to learn, enabling you to build powerful applications quickly.  
**TensorFlow Lite**: An open-source framework for performing deep learning tasks directly on devices.  
**CameraX**: A Jetpack library designed to simplify and enhance camera app development.  
**Jetpack Compose**: Android's modern UI toolkit for building native interfaces faster and with less complexity.  
**Retrofit**: A type-safe HTTP client for Android and Java, ideal for handling API communication.  
**Firebase**: A comprehensive app development platform offering backend services like real-time databases, cloud storage, authentication, crash reporting, machine learning, and static file hosting.  

## Features

**History Page** <br>
To save all the photo that has been scanned, this will save into backend server.

**Scan Page** <br>
This page allows users to scan fonts they want to identify. If users wish to save the results, they can capture the font using the capture button. The results will then be stored in the history page.

**Settings Page** <br>
This page provides two customization options: theme and language. Users can switch between dark mode and light mode for the theme. For language, they can choose between Indonesian and English.

## How To Use as Developer

1. clone this repository
   ```
   git clone https://github.com/FontFound/FontFound-Mobile.git
   ```
2. Open the project in android studio
3. run the project using mobile phone (emulator not recomended)

## How To Use as User

1. Donwload the app from this link https://github.com/FontFound/FontFound-Mobile/releases
2. install the app
3. enjoy
