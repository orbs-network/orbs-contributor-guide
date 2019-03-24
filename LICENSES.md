# Licenses

The default license for the Orbs project repos is MIT.

To add the license to a repo, follow these instructions:

&nbsp;
### 1. Create a file named `LICENSE` (no extension) at the root of the repo with this content:

```
MIT License

Copyright (c) 2019 Orbs

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
```

&nbsp;
### 2. Create a file named `LICENSE-HEADER` (no extension) at the root of the repo with this content:

```
Copyright 2019 the <REPO-NAME> authors
This file is part of the <REPO-NAME> library in the Orbs project.

This source code is licensed under the MIT license found in the LICENSE file in the root directory of this source tree.
The above notice should be included in all copies or substantial portions of the software.

```

&nbsp;
### 3. In the file `LICENSE-HEADER` replace `<REPO-NAME>` with the actual repo name

For example `orbs-network-go` or `membuffers`

&nbsp;
### 4. To add the license header to all source files, install the following command line tool:

```
go get -u github.com/orbs-network/addlicense
```

make sure gopath/bin is in your path (``export PATH=$PATH:`go env GOPATH`/bin``)

&nbsp;
### 5. Run the command line tool from the repo root:

```
addlicense -f LICENSE-HEADER .
```
