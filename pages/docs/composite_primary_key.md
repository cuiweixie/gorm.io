title: Composite Primary Key
---

Set multiple fields as primary key to enable composite primary key

```go
type Product struct {
	ID           string `gorm:"primary_key"`
	LanguageCode string `gorm:"primary_key"`
}
```

