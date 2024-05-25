# Git-Issues
git-issues` is a Python command-line tool that allows users to fetch and export GitHub repository issues to CSV and PDF formats. It is designed to work on Python 3.11 and has been tested on Ubuntu 23.04.


Certainly! Below is a sample `README.md` file for your Python package `git-issues`. This markdown document provides potential users with a brief overview of what the package does, how to install it, how to use it, and where to get help or contribute. Adjust the content as necessary to fit your package's specifics and your GitHub repository URL.

```markdown
# git-issues

`git-issues` is a Python command-line tool that allows users to fetch and export GitHub repository issues to CSV and PDF formats. It is designed to work on Python 3.11 and has been tested on Ubuntu 23.04.

## Features

- Fetch all open and closed issues from any public GitHub repository.
- Export the list of issues to a CSV file.
- Export the issues in a tabular format to a PDF file, with clickable links to the issues.

## Installation

To install `git-issues`, you'll need Python 3.11 or higher. It's recommended to use a virtual environment:

```bash
python3 -m venv env
source env/bin/activate
```

Clone the repository and install the package:

```bash
git clone https://github.com/yourgithubusername/git-issues.git
cd git-issues
pip install .
```

## Usage

Once installed, you can run `git-issues` from the command line:

```bash
git-issues <owner> <repo> [--state <state>]
```

- `<owner>`: GitHub username or organization under which the repository exists.
- `<repo>`: Repository name.
- `--state`: The state of issues to fetch (`all`, `open`, or `closed`). Defaults to `all`.

Example:

```bash
git-issues IBT-learning full-stack-software-engineering-2024 --state open
```

This command will fetch all open issues from the specified repository and save them in both CSV and PDF formats in the current directory.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue on the [GitHub repository](https://github.com/yourgithubusername/git-issues).

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For support or any questions, feel free to contact me at:

- Adesoji Alu - adesoji.alu@gmail.com
```

### Key Sections of the README

- **Features**: Highlights the main functionality of the package.
- **Installation**: Provides step-by-step instructions on how to install the package.
- **Usage**: Explains how to use the command-line tool with examples.
- **Contributing**: Encourages community involvement.
- **License**: Notes the type of license under which your package is released.
- **Contact**: Offers a way for users to reach out with questions or support requests.

