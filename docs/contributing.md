Welcome to the `Instructor` project! We would love for you to contribute to `Instructor`.
  
## [Evals](https://github.com/jxnl/instructor/tree/main/tests/openai/evals)

We invite you to contribute evals in pytest as a way to monitor the quality of the openai models and the instructor library. To get started check out the [jxnl/instructor/tests/evals](https://github.com/jxnl/instructor/tree/main/tests/openai/evals) and contribute your own evals in the form of pytest tests. These evals will be run once a week and the results will be posted.

## Issues

If you find a bug, please file an issue on [our issue tracker on GitHub](https://github.com/jxnl/instructor/issues).

To help us reproduce the bug, please provide a minimal reproducible example, including a code snippet and the full error message.


##Example: 

```python
# Minimal Reproducible Example
from instructor import Instructor

def reproduce_issue():
    # Instantiate the Instructor
    instructor = Instructor()

    # Define a sample response model
    response_model = {
        "status": "success",
        "message": "Hello, Instructor!",
    }

    # Simulate a bug
    result = instructor.evaluate(response_model)

    # Your code here to reproduce the issue
    # ...

    return result


1. The `response_model` you are using.
2. The `messages` you are using.
3. The `model` you are using.

## Interactive Example:

To provide an interactive example, let's use the evaluate function with the provided example:

python

# Interactive Example
from instructor import Instructor

# Instantiate the Instructor
instructor = Instructor()

# Define a sample response model
response_model = {
    "status": "success",
    "message": "Hello, Instructor!",
}

# Use the evaluate function
result = instructor.evaluate(response_model)

# Display the result
print(result)

This interactive example demonstrates how to use the evaluate function with the provided response_model. Feel free to experiment with different response models and observe the output.

## Pull Requests

We welcome pull requests! There is plenty to do, and we are happy to discuss any contributions you would like to make.

If it is not a small change, please start by [filing an issue](https://github.com/jxnl/instructor/issues) first.

If you need ideas, you can check out the [help wanted](https://github.com/jxnl/instructor/labels/help%20wanted) or [good first issue](https://github.com/jxnl/instructor/labels/good%20first%20issue) labels.



## Additional Resources

To improve the legibility of code and content, consider using the following features:

You can use the following command to install the required packages: pip install mkdocs mkdocs-material mkdocs-minify-plugin mkdocstrings mkdocs-rss-plugin "mkdocs-material[imaging]" "mkdocstrings[python]"

- **mkdocs serve:** The `mkdocs serve` command is used to preview your documentation locally during the development phase. When you run this command in your terminal, MkDocs starts a development server, allowing you to view and interact with your documentation in a web browser. This is helpful for checking how your changes look before publishing the documentation. Learn more in the [mkdocs serve documentation](https://www.mkdocs.org/user-guide/cli/#mkdocs-serve) or at https://www.mkdocs.org/user-guide/installation/


- **hl_lines in Code Blocks:** The `hl_lines` feature in code blocks allows you to highlight specific lines within the code block. This is useful for drawing attention to particular lines of code when explaining examples or providing instructions. You can specify the lines to highlight using the `hl_lines` option in your code block configuration. For more details and examples, you can refer to the [hl_lines documentation](https://www.mkdocs.org/user-guide/writing-your-docs/#syntax-highlighting).

- **Admonitions:** Admonitions are a way to visually emphasize or call attention to certain pieces of information in your documentation. They come in various styles, such as notes, warnings, tips, etc. Admonitions provide a structured and consistent way to present important content. For usage examples and details on incorporating admonitions into your documentation, you can refer to the [admonitions documentation](https://www.mkdocs.org/user-guide/writing-your-docs/#admonitions).

To run the docs, install the required dependencies using `pip install -r requirements-doc.txt` and run `mkdocs serve -w .` to preview the documentation.


# Contributors

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

<a href="https://github.com/jxnl/instructor/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=jxnl/instructor" />
</a>
