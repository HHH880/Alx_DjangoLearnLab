# Delete Book

This document demonstrates how to delete an existing book record using Django ORM.

## Example

```python
from bookshelf.models import Book

book = Book.objects.get(title="Nineteen Eighty-Four")
book.delete()
