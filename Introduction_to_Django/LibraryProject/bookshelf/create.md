# Create Book

This document demonstrates how to create a Book record using the Django ORM.

## Example

```python
from bookshelf.models import Book

Book.objects.create(
    title="1984",
    author="George Orwell"
)
