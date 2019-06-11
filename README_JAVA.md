
### How change your code from *Default* Android Studio code style?

#### Code Style - Generic
- Right margin: keep your lines within **200** characters width.


#### Code Style - Java
##### Wrapping and Braces
- When reformatting code don't keep anything.
- Avoid align when multiline and wrap following statements if long:
 - Extends/implements list
 - Extends/implements keyword
 - Throws list
 - Throws keyword
 - Method declararion parameters
 - Method call arguments

- Always use brackets for `if` / `for` / `while` / `do-while` statements. Even if its a one-liner.
- Write follow up `else` clauses after the previous closing bracket on the same line.
- Use new line after '{' and before '}' for array initialization statement.

##### Blank Lines
- Keep maximum blank lines to 1.

##### JavaDoc
- Avoid alignment of parameter and thrown exception descriptions.
- Use blank line after description and return tag.
- No `<p>` on empty lines.

##### Imports
- Never use fully qualified class name in JavaDoc, use short name and add import instead.

##### Code Generation
- Use naming convention as follow:
 - Field name prefix: `m`
 - Static field name prefix: `s`
- Align line and block comment to code, don't use first colum approach.


#### Code Style - XML
##### Tabs and Indents
- Use 4 spaces for indentation and alignment. Do not use tabs.

##### Other
- Keep line breaks.
- Don't wrap text.
- Align attributes.
- Don't use space in empty tag.

##### Android
- AndroidManifest: use *Do not wrap* for wrap attributes approach and insert line break after node last attribute.
- Other XML resource files: use *Do not wrap* for wrap attributes approach.



## License

Copyright (C) 2017 Sysdata, S.p.a.

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.