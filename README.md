# Riskmod GPT

Riskmod GPT is an AI-powered threat modeling tool that leverages OpenAI's GPT models to generate threat models and attack trees for a given application based on the STRIDE methodology. Users provide application details, such as the application type, authentication methods, and whether the application is internet-facing or processes sensitive data. The GPT model then generates its output based on the provided information.

## Table of Contents
- [Star the Repo](#star-the-repo)
- [Features](#features)
- [Changelog](#changelog)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Star the Repo

If you find Riskmod GPT useful, please consider starring the repository on GitHub. This helps more people discover the tool. Your support is greatly appreciated! ⭐

## Features
- Simple and user-friendly interface
- Generates threat models based on the STRIDE methodology
- Generates attack trees to enumerate possible attack paths
- Suggests possible mitigations for identified threats
- Utilises OpenAI's powerful GPT models for AI-driven threat analysis
- No data storage; application details are not saved

## Changelog

### Version 0.1

Initial release of the application.

## Installation

1. Clone this repository:

```
git clone https://github.com/cintelis/riskmod-gpt.git
```

2. Change to the cloned repository directory:

```
cd riskmod-gpt
```

3. Install the required Python packages:

```
pip install -r requirements.txt
```

**Note:** 📝 Streamlit should **not** be included in requirements.txt as it causes the Streamlit deployment process to fail.

## Usage

1. Run the Streamlit app:

```
streamlit run main.py
```

2. Open the app in your web browser using the provided URL.

3. Enter your OpenAI API key in the sidebar.

4. Provide the application details and select the appropriate options.

5. Navigate to the Threat Model and/or Attack Tree section and click the "Generate..." button.

6. Review the generated threat model and/or attack tree and, if required, download a markdown copy of the output.

7. If you want to generate suggested mitigations for the identified threats, go to the "Mitigations" section and click the "Suggest Mitigations" button.

8. Review the suggested mitigations and, if required, download them as a Markdown file.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)