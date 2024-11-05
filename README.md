# PicMorpher

## Introduction

PicMorpher is an innovative AI web application that transforms textual prompts into captivating images, offering a seamless intersection of creativity and technology. This project, led by Afua Addae Adjei-Arthur, was developed as a solo endeavor and serves as the final project for the foundations section of the ALX Software Engineering program.

- **Deployed Site:** [PicMorpher](https://picmorpher.onrender.com)
- **Final Project Blog Article:** [Unleashing Creativity: The PicMorpher Journey](https://www.linkedin.com/pulse/unleashing-creativity-picmorpher-journey-afua-addae-adjei-arthur-ma-dka1e)
- **Author(s) LinkedIn:** [Afua Addae Adjei-Arthur](www.linkedin.com/in/afua-addae-adjei-arthur-afua)

## Installation

To run PicMorpher locally, follow these installation steps:

1. Clone the repository using the command: `git clone [https://github.com/afuawonders/PicMorpher-App.git]`.
2. Navigate to the project directory: `cd PicMorpher`.
3. Install dependencies: `npm install`.
4. Configure the OpenAI API key in the `config.js` file.

## Usage

- **Authentication:**
  - **Login:**
    - Endpoint: `/api/v1/auth/login`
    - Method: POST
    - Returns: User Token
    - Request: `{ "email": "your-email@example.com", "password": "your-password" }`

  - **Signup:**
    - Endpoint: `/api/v1/auth/signup`
    - Method: POST
    - Returns: User Token
    - Request: `{ "email": "your-email@example.com", "password": "your-password", "first_name": "your-first-name", "last_name": "your-last-name" }`

- **Image Generation Route:**
  - Endpoint: `/api/v1/generate-images`
  - Method: POST
  - Returns: Image URL based on a text prompt
  - Request: `{ "prompt": "A LION CHASING A HUMAN", "size": "small" }`

## Contributing

Contributions to PicMorpher are welcome! To contribute, follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push the changes to your fork.
5. Submit a pull request.

## Related Projects

1. **Deep Dream Generator:**
   - [Deep Dream Generator](https://deepdreamgenerator.com)
   - Applies neural network algorithms to create dreamlike visuals.

2. **DALL-E by OpenAI:**
   - A model generating images from textual descriptions, developed by OpenAI, known for creating unique visuals.

## Licensing

This project is licensed under the [MIT-license, Tricks-license, ] License - see the [LICENSE.md](LICENSE.md) file for details.

