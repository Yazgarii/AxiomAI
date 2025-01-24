\# Axiom

This project is an artificial intelligence platform developed to provide
solutions for software design and help. The project provides a powerful
user experience using the \*\*Gemini\*\* and \*\*ChatGPT-3\*\* APIs.
JavaScript\*\* was preferred as the development language.

\-\--

\## Features

\- \*\*Software Design Assistant\*\*: Analyzes the requirements received
from the user and provides suggestions. - Code Completion and
Debugging\*\*: Detects faulty code, suggests fixes and adds comments. -
\*\*Natural Language Interaction\*\*: Communicates with users in a
natural language. - API Integrations\*\*: Powerful text analytics and
response generation capabilities with Gemini and ChatGPT-3 APIs.

\-\--

\## Getting Started

This project has a structure suitable for both beginners and experienced
developers. You can run the project quickly by following the
installation steps.

\#### Requirements

\- Node.js (v14 or higher) - NPM or Yarn

\-\--

\## Installation

1\. \*\*Clone the Warehouse:\*\* \`\`\`bash git clone
https://github.com/AxiomAI/ai-project.git cd ai-project \`\`\`

2\. \*\*Install Dependencies:\*\* \`\`\`bash npm install \`\`\`

3\. \*\*Configure API Keys:\*\* Create a \`config.js\` file in the
project root directory and add your API keys as follows: \`\`javascript
export const config = { GEMINI_API_KEY: \'your-gemini-api-key\',
CHATGPT_API_KEY: \'your-chatgpt-api-key\' }; \`\`\`

4\. \*\*Run the Application:\*\* \`\`\`bash npm start \`\`\`

5\. Open your browser and go to the following address: \`\`\`
http://localhost:3000 \`\`\`

\-\--

\## Technologies Used

\| Technology \| Description \|
\|\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--\|\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--\|
\*\*JavaScript\*\* \| Main development language \*\*Node.js\*\* \|
Backend development platform \| \*\*Gemini API\*\* \| Data analysis and
prediction engine \| \| \*\*ChatGPT-3\*\* \| Natural language processing
\| \*\*HTML/CSS\*\* \| Interface development \|

\-\--

\## File Structure

\`\`\` root ├── index2.html \# Home page ├── script.js \# Main
JavaScript file ├── style2.css \# Style files ├── api \# API related
modules │ ├── index.html \# AI Page │ └─── style.css \# AI page style
file └── assets \# Images and static files \`\`\`

\-\--

\## API Usage

\### Gemini API

\`\`javascript fetch(\'https://gemini.api/endpoint\', { method:
\'POST\', headers: { \'Content-Type\': \'application/json\',
\'Authorization\': \'Bearer YOUR_API_KEY\' }, body: JSON.stringify({
input: \'User input\' }) }) .then(response =\> response.json())
.then(data =\> console.log(data)); \`\`\`

\#### ChatGPT-3 API

\`\`javascript fetch(\'https://api.openai.com/v1/completions\', {
method: \'POST\', headers: { \'Content-Type\': \'application/json\',
\'Authorization\': \'Bearer YOUR_API_KEY\' }, body: JSON.stringify({
model: \'text-davinci-003\', prompt: \'Hello! How can I help you?\',
max_tokens: 150 }) }) .then(response =\> response.json()) .then(data =\>
console.log(data.choices\[0\].text)); \`\`\`

\-\--

\## Contribution

Contributions are always welcome! Please follow these steps:

1\. Fork this project. 2. Create your own branch (\`git checkout -b
feature/feature-name\`). 3. Commit your changes (\`git commit -m \'I
added a new feature\'\`). 4. Push your branch (\`git push origin
feature/feature-name\`). 5. Open a Pull Request.

\-\--

\## Troubleshooting

\- \*\*API Errors:\*\* Make sure your API keys are correct. - Connection
Problems:\*\* Check your internet connection and API access permissions.

\-\--

\## License

This project is licensed under the MIT License. Check the \[LICENSE
file\] for more information.

\-\--

\## Contact

For questions or feedback, please contact us at
(mailto:yagizberk49@gmail.com).

Thank you! 🎉
