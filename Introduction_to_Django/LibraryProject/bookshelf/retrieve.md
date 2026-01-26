# Retrieve Book

This document shows how to retrieve book records from the database using Django ORM.

## Example

```python
from bookshelf.models import Book

Book.objects.get(title="1984")
