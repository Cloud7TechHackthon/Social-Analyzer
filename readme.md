# Social Media Analyzer (RAG)

Welcome to the *Social Media Analyzer (RAG)* project! This repository showcases an innovative platform for analyzing social media performance using *LangFlow* and *DataStax Astra DB*.

## Folder Structure

### 1. Social Media Analyzer RAG
This folder contains the LangFlow JSON model file.

- *Import the LangFlow JSON Model*: Use this JSON file to quickly set up and visualize workflows in LangFlow.
- *Customizations*: Replace the API keys and configure the model for your use case.

### 2. social_analyzer
This folder contains the Next.js application that utilizes the LangFlow API for data processing and insights generation.

#### Configuration:
Ensure the following environment variables are correctly set in your .env.local file:
env
NEXT_PUBLIC_FLOW_ID_OR_NAME=<Your Flow ID or Name>
NEXT_PUBLIC_LANGFLOW_ID=<Your LangFlow ID>
NEXT_PUBLIC_APPLICATION_TOKEN=<Your Application Token>


## Getting Started

### Prerequisites
- Node.js 
- Yarn or npm
- LangFlow installed locally or accessible via URL
- DataStax Astra DB account and credentials

### Steps to Run the Project

#### LangFlow Setup
1. Navigate to the Sma Rag folder.
2. Import the JSON model into LangFlow:
   - Open LangFlow.
   - Click on *Import Workflow*.
   - Upload the provided JSON file.
3. Replace API keys in the LangFlow interface to match your setup.

#### Next.js Application Setup
1. Navigate to the social_analyzer folder:
   bash
   cd social_analyzer
   
2. Install dependencies:
   bash
   yarn install
   # or
   npm install
   
3. Create a .env.local file and populate it with the environment variables:
   env
   NEXT_PUBLIC_FLOW_ID_OR_NAME=<Your Flow ID or Name>
   NEXT_PUBLIC_LANGFLOW_ID=<Your LangFlow ID>
   NEXT_PUBLIC_APPLICATION_TOKEN=<Your Application Token>
   
4. Start the development server:
   bash
   yarn dev
   # or
   npm run dev
   
5. Open the application in your browser:
   
   http://localhost:3000

### Features
- Real-time social media data analysis.
- Customizable insights tailored for different post types (carousel, reels, static).
- Scalable architecture powered by *DataStax Astra DB*.

## Contributions
We welcome contributions from the community! Please open an issue or submit a pull request if you have ideas to improve this project.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
*Team Cloud7Tech*:
- Nisarg Shah
- Sandeep Swain
- Nihar Bharatia
- Parag Vadgama

For questions or collaborations, feel free to reach out to us.

---

### Links
- [LangFlow](https://langflow.org)
- [DataStax Astra DB](https://www.datastax.com/astra)
- [Youtube](https://youtu.be/Pjc-E_1QfhU)
