# FITS Files Analysis (Python)

A collection of Jupyter notebooks for analyzing astronomical FITS images using Python.

Built from real astrophotography data captured with a Seestar S50.

---

## Notebooks

| Notebook | Description |
|----------|-------------|
| [01 Loading FITS](loading_fits.ipynb) | Load a FITS file, read metadata, display the raw image |
| [02 Image Stretching](Image%20Stretching.ipynb) | ZScale and Asinh stretching methods |
| [03 Nebula Analysis](nebula%20analysis.ipynb) | Brightness map, contours, star detection, SNR |
| [04 Moon Analysis](Moon%20analysis.ipynb) | Surface detail, brightness profile, edge detection |
| [05 Solar Analysis](Sun%20analysis.ipynb) | Sunspot detection, limb darkening |

---

## Requirements

```bash
pip install astropy numpy matplotlib photutils scipy
```

---

## Notes

- All notebooks use `your_image.fits` as a placeholder replace with your actual file path
- Stretching parameters (like `a=0.01`) can be adjusted based on your image
- Star detection parameters (`fwhm`, `threshold`) depend on your telescope and seeing conditions
