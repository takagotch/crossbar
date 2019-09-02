### crossbar
---
https://github.com/crossbario/crossbar/

```py
// crossbar/test/test_compat.py

class NativeStringTestCase(TestCase):
  def test_bytes_always_native(self):
    self.assertEqual(type(compat.native_string(b"foo")), str)
    
  def test_unicode_not_allowed(self):
    with self.assertRaises(ValueError):
      compat.native_string(u"bar")
```

```
```

```
```


