# Update Book

This document demonstrates how to update an existing book record using Django ORM.

## Example

```python
from bookshelf.models import Book

book = Book.objects.get(title="1984")
book.author = "George Orwell"
book.save()
