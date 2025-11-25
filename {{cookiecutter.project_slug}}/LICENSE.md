{# LICENSE #}
{% if cookiecutter.license == "MIT" -%}
### MIT License

Copyright (c) 2026 [{{ cookiecutter.author_name }}]

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

{% elif cookiecutter.license == "Apache 2.0" -%}
### Apache 2.0 License

Copyright 2026 {{ cookiecutter.author_name }}

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.


{% elif cookiecutter.license == "Not Open Source" -%}
### Proprietary and Confidential Software License

**Project:** {{ cookiecutter.project_name }}

**Copyright (C) 2026 {{ cookiecutter.author_name }}**
**All Rights Reserved.**

This software, including all source code, object code, documentation, and related data (the "Software"), is the proprietary and confidential information of **{{ cookiecutter.author_name }}**.

**1. Ownership and Rights:**
The copyright in the Software is owned by **{{ cookiecutter.author_name }}**. The Software is protected by copyright laws and international treaty provisions.

**2. Restrictions on Use:**
Unauthorized copying, reverse engineering, decompilation, disassembly, or distribution of this Software, in whole or in part, is strictly prohibited. You may not modify, adapt, merge, translate, or create derivative works based on the Software.

**3. No Warranty:**
The Software is provided "AS IS," without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and non-infringement. In no event shall the authors or copyright holders be liable for any claim, damages, or other liability arising from the use or inability to use the Software.

**4. Contact Information:**
For specific licensing questions, please contact **{{ cookiecutter.author_name }}**.
{% endif -%}
