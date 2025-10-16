git clone https://github.com/your-username/employee-dashboard-test.git
    cd employee-dashboard-test
    ```
    (Replace `https://github.com/your-username/employee-dashboard-test.git` with the actual repository URL if hosted.)

2.  **Ensure `employees.csv` is present:**
    Make sure an `employees.csv` file is located in the root directory of the project. This file should contain your employee data, typically with columns like `name`, `salary`, etc., though only salary is strictly needed for the average salary calculation.

3.  **Open the application in your browser:**
    You can directly open the `index.html` file in your web browser. Due to browser security restrictions regarding local file access (e.g., `file://` protocol), it's often better to serve the project using a simple local HTTP server.

    **Using a local HTTP server (recommended):**
    If you have Python installed, you can use its built-in server:
    ```bash
    python -m http.server 8000
    ```
    Then, open your web browser and navigate to `http://localhost:8000`.

    If you prefer Node.js, you can install `http-server`:
    ```bash
    npm install -g http-server
    http-server -p 8000
    ```
    Then, navigate to `http://localhost:8000`.

    Once loaded, the webpage will display the total employee count and the calculated average salary.

## License
This project is licensed under the MIT License.

```
MIT License

Copyright (c) [Year] [Your Name or Project Maintainers]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.