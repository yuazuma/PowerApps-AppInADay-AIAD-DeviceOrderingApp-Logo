# PowerApps-AppInADay-AIAD-DeviceOrderingApp-Logo

---

```
MainScreen > ManufacturerGallery > Image3 . Image
```

```
If(
    IsBlank(ThisItem.'Logo@display'),
    ThisItem.Logo,
    ThisItem.'Logo@display'
)
```
