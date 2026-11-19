# Notice for unidic-accent-3.1.0.sqlite.gz

This data-only repository holds one derived table: the accent type (pitch accent) of each base form and reading found in
UniDic-cwj 3.1.0 (344508 rows). It contains no program code. The table is derived from the UniDic
lexicon file `lex_*.csv` of the package published by NINJAL (National Institute for Japanese Language and Linguistics) at
https://clrd.ninjal.ac.jp/unidic_archive/cwj/3.1.0/ ; the source zip has SHA-256 340651aa78cc02caf690f94de8809d41c4acda694226517884ecad81c51523fc.
UniDic is copyrighted free software of The UniDic Consortium, released under the GPL, the LGPL or the BSD License, at the
user's choice. This table is distributed under the BSD License below. The name of the UniDic Consortium or its contributors
is not used to endorse or promote anything built from this table.

## BSD License (verbatim from the package, `liceses/BSD`)

```
Copyright (c) 2011-2021, The UniDic Consortium
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are
met:

 * Redistributions of source code must retain the above copyright
   notice, this list of conditions and the following disclaimer.

 * Redistributions in binary form must reproduce the above copyright
   notice, this list of conditions and the following disclaimer in the
   documentation and/or other materials provided with the
   distribution.

 * Neither the name of the UniDic Consortium nor the names of its
   contributors may be used to endorse or promote products derived
   from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS
"AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT
LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR
A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT
OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT
LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE,
DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY
THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
```

## Rebuilding

`python -I -X utf8 tool/unidic_accent_table.py unidic-cwj-3.1.0.zip <out dir>` (script in the Terra project).
