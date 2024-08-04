<a href="https://warriorwhocodes.com"><img src="repo_images/header.jpg"></a>

<p align="center">
  <a href="https://ankushsinghgandhi.github.io">
    <img src="https://img.shields.io/badge/Website-3b5998?style=flat-square&logo=google-chrome&logoColor=white" />
  </a>
  <a href="http://twitter.com/ankushsgandhi">
    <img src="https://img.shields.io/badge/-Twitter-blue?style=flat-square&logo=twitter&logoColor=white" />
  </a>
   <a href="https://www.linkedin.com/in/ankush-singh-gandhi-2487771aa/">
    <img src="https://img.shields.io/badge/-LinkedIn-0e76a8?style=flat-square&logo=Linkedin&logoColor=white" />
  </a>
  <a href="https://dev.to/@ankushsinghgandhi">
    <img src="https://img.shields.io/badge/-Dev.to-grey?style=flat-square&logo=dev.to&logoColor=white"/>
  </a>
  <a href="https://stackoverflow.com/users/13790266/ankush-singh">
    <img src="https://img.shields.io/badge/-Stackoverflow-orange?style=flat-square&logo=stackoverflow&logoColor=white"/>
  </a>
  <a href="https://leetcode.com/ankushsinghgandhi/">
    <img src="https://img.shields.io/badge/-Leetcode-yellow?style=flat-square&logo=Leetcode&logoColor=white"/>
  </a>
    <a href="https://www.hackerrank.com/ankushsgandhi">
    <img src="https://img.shields.io/badge/-HackerRank-green?style=flat-square&logo=Hackerrank&logoColor=white"/>
  </a>
    <a href="https://www.hackerearth.com/@bhanusinghank">
    <img src="https://img.shields.io/badge/-Hackerearth-purple?style=flat-square&logo=Hackerearth&logoColor=white"/>
  </a>
</p>

# Traveler Backend Flask

The goal of this project is to build and integrate web services to form a comprehensive travel agency application. The application includes a flight booking service, currency conversion service, and additional value-added functionalities through external REST APIs.

## Features

### Core Web Service Implementation
1. **Flight Booking Service**
   - Manages available travel offers stored in a JSON Array.
   - Implements search functionality allowing customers to find suitable flights based on various criteria.
   - Includes methods for booking flights and updating available seats.

2. **Currency Conversion Service**
   - Integrates an external currency conversion service to auto-convert ticket prices to the customer’s preferred currency.

### Web Service Composition and Deployment
3. **Extended Functionality**
   - Utilizes external RESTful services to offer driving directions and additional information about destinations.
   - Deployment improvements using containerization with Docker.

### Quality of Service Analysis
4. **Performance and Scalability**
   - Analysis of SOA Web Services’ performance and scalability challenges.
   - Discussion on how Cloud Computing and containerization can address these issues.

### Semantic Web and Linked Data Technologies
5. **Advanced Integration**
   - Critical analysis of Semantic Web technologies and Linked Open Data.
   - Integration of public datasets to recommend themed holidays matching client profiles.

## Technologies Used

- **Flask**: Backend framework for developing web services.
- **Docker**: For containerizing the application to facilitate deployment.
- **REST APIs**: Integration of various external services for added functionality.
- **JMeter**: For performance testing and quality of service analysis.

## Getting Started

### Prerequisites

- Python 3.x
- Flask
- Docker
- JMeter (for QoS testing)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ankushsinghgandhi/traveler_backend_flask.git
   ```
2. Navigate to the project directory:
   ```bash
   cd project-repo
   ```
3. Set up the virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```
4. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Application

1. Start the Flask server:
   ```bash
   flask run
   ```
2. Access the application at `http://localhost:5000`

### Docker Deployment

1. Build the Docker image:
   ```bash
   docker build -t project-image .
   ```
2. Run the Docker container:
   ```bash
   docker run -p 5000:5000 project-image
   ```

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


