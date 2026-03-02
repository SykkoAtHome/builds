# builds

Repozytorium z gotowymi buildami pakietow.

## Zawartosc

Aktualnie repo zawiera wheel'e `gsplat` dla Windows:

- `gsplat/win/gsplat-1.5.3-cu130-cp312-win_amd64.whl`
- `gsplat/win/gsplat-1.5.3-cu130-cp314-win_amd64.whl`

## Instalacja (lokalnie z pliku)

PowerShell, Python 3.12:

```powershell
python -m pip install .\gsplat\win\gsplat-1.5.3-cu130-cp312-win_amd64.whl
```

PowerShell, Python 3.14:

```powershell
python -m pip install .\gsplat\win\gsplat-1.5.3-cu130-cp314-win_amd64.whl
```

## Wymagania

- Windows x86_64
- Zgodna wersja Pythona (`cp312` albo `cp314`)
- CUDA 13.0 (`cu130`)
