# Autogram: Your Instagram Engagement Assistant

Autogram is a Python package designed to help boost your friends' engagement scores on Instagram. Leveraging the powerful capabilities of the [Instagrapi](https://github.com/realsirjoe/instagram-private-api) Python package, Autogram helps you automate several user engagement tasks, allowing you to keep a constant presence on Instagram with minimal effort. 

Please note that Instagram has policies against certain types of automation. Autogram is intended to be used responsibly, in a manner that respects Instagram's rules and community guidelines.

## Features

- **Automatic Liking:** Autogram can automatically like your friends' posts on Instagram, helping to improve their engagement rates.
- **Automated Comments:** The package can post comments on your friends' posts. Comment templates can be customized and rotated to maintain a natural, authentic feel.
- **Ease of Use:** With a straightforward setup process and user-friendly commands, Autogram is easy to integrate into your social media workflow.

## Installation

To install Autogram, simply run the following command:

```bash
pip install autogram
```

## Usage

First, import the Autogram package.

```python
from autogram import Autogram
```

Next, initialize an Autogram instance with your Instagram username and password.

```python
autogram = Autogram('your_username', 'your_password')
```

To automatically like your friends' posts:

```python
autogram.auto_like('friend_username')
```

To post automated comments on your friends' posts:

```python
comments = ["Great post!", "Love this!", "This is awesome!"]
autogram.auto_comment('friend_username', comments)
```

## Disclaimer

Autogram is designed to be a tool for engaging with your friends and boosting their Instagram engagement scores. It should not be used for spamming or violating Instagram's community guidelines. Users are responsible for using Autogram in a responsible and ethical manner.

## Contributions

Contributions are more than welcome. Please fork this repository and submit a pull request with your changes.

## License

Autogram is released under the MIT License. See the LICENSE file for more details.

---
For more details on how to use Autogram, please refer to our [documentation](LINK_TO_DOCUMENTATION).
