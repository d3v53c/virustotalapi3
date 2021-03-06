.. _error-label:

VirusTotalAPIError
==================

A class that implements exceptions that may occur when module class methods are used.

Types of exceptions:
--------------------

- **"Connection error":** This exception occurs when there is an error communicating with the server (Error code = errno.ECONNABORTED_)
- **"Timeout error":** This exception occurs when the response time from the server is exceeded (Error code = errno.ETIMEDOUT_).
- **"File not found":** This exception occurs when the file to be uploaded to the server is not found (Error code = errno.ENOENT_).
- **"Permission error":** This exception occurs when the file to be uploaded to the server is not found (Error code = errno.EPERM_).
- **"IO Error":** (Added in version 1.1.1) This exception occurs if there is an IO error during file operations (Error code = errno.EIO_).
- **"API key environment error:" (Added in version 1.1.2) This exception occurs if the VT_API_KEY environment variable with the VirusTotal API function access key is missing (Error code = errno.EINVAL_).

.. _errno.ECONNABORTED: https://docs.python.org/2/library/errno.html
.. _errno.ETIMEDOUT: https://docs.python.org/2/library/errno.html
.. _errno.ENOENT: https://docs.python.org/2/library/errno.html
.. _errno.EPERM: https://docs.python.org/2/library/errno.html
.. _errno.EIO: https://docs.python.org/2/library/errno.html
.. _errno.EINVAL: https://docs.python.org/2/library/errno.html
