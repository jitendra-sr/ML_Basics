_Creating isolated environments is a great practice to avoid dependency conflicts and keep projects separate. We can create multiple virtual environments and switch between them easily.
We can do that using venv, which is a built-in tool in Python for creating isolated environments._

## Create a New Virtual Environment

1. cd C:\path\to\your\project
2. python -m venv myenv
3. myenv\Scripts\activate

## Deactivate the Environment

4. deactivate

## Delete the Environment

5. rmdir /s myenv

## Switch environments

6. Deactivate the current environment if active.
7. cd path\to\your\other\project
8. myenv2\Scripts\activate
