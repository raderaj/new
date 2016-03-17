# pandas_SAS_snippets
Simple repo containing a test file for the sas7bdat.py file.

I reached an error on line 334 in this file (an else clause) that attempts to execute the following line:
``` buf = self._path_or_buf.read(_os_maker_offset, _os_maker_length) ```

The test file is
* productsales.sas7bdat

I've also uploaded a version of sas7bdat.py that changes `read` to `_read_buf`
