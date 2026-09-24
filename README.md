# tl_ole

Eduardo A. Morcillo (Edanmo) OLE/ActiveX toolkit: `olelib.tlb`/`.odl` plus `.inc` interface headers and sample projects (IOleObject extents, context menus, IDispatch invoke, property pages, ActiveDesktop, component categories, TypeInfo). Sensitive typelib bits may be redacted to `*.example`. Open any sample `.vbp` under `Samples/` in the VB6 IDE.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** ActiveX OCX, WinForms exe

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `prjIOleObjectExtent` (`Samples/Extents/IOleObject Extent.vbp`) | VB6 | ActiveX OCX | IOleObject.GetExtent Sample |
| `Project2` (`Samples/Extents/Test.vbp`) | VB6 | WinForms exe | Project2 |
| `Project1` (`Samples/TypeInfo Sample 2/Project1.vbp`) | VB6 | WinForms exe | Project1 |
| `Project2` (`Samples/Specify Property Pages/TestProject.vbp`) | VB6 | WinForms exe | Project2 |
| `axISPPSample` (`Samples/Specify Property Pages/axISPPSample.vbp`) | VB6 | ActiveX OCX | axISPPSample |
| `ActiveDesktop` (`Samples/ActiveDesktop/ActiveDesktop.vbp`) | VB6 | WinForms exe | ActiveDesktop Sample |
| `prjCatMgrTest` (`Samples/ComponentCategoriesMgr/CatMgrText.vbp`) | VB6 | WinForms exe | prjCatMgrTest |
| `prjCtxMenus` (`Samples/Context Menu/UC Ctx Menu.vbp`) | VB6 | ActiveX OCX | Context Menu Sample |
| `Project2` (`Samples/Context Menu/Test.vbp`) | VB6 | WinForms exe | Project2 |
| `Project1` (`Samples/TypeInfo sample/Project1.vbp`) | VB6 | WinForms exe | Project1 |
| `IDspSample` (`Samples/Invoke sample/Project1.vbp`) | VB6 | WinForms exe | IDispatch Invoke Sample |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `Samples/Extents/IOleObject Extent.vbp`
- `Samples/Extents/Test.vbp`
- `Samples/TypeInfo Sample 2/Project1.vbp`
- `Samples/Specify Property Pages/TestProject.vbp`
- `Samples/Specify Property Pages/axISPPSample.vbp`
- `Samples/ActiveDesktop/ActiveDesktop.vbp`
- `Samples/ComponentCategoriesMgr/CatMgrText.vbp`
- `Samples/Context Menu/UC Ctx Menu.vbp`
- `Samples/Context Menu/Test.vbp`
- `Samples/TypeInfo sample/Project1.vbp`
- `Samples/Invoke sample/Project1.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Registered OCX/DLL dependencies referenced by the `.vbp` (may need to be installed separately):
  - `COMCTL32.OCX`
  - `COMDLG32.OCX`
  - `RICHTX32.OCX`

## Attribution and provenance

Working copy from my Historical Dev folder `VB/tl_ole`.
Company names in `.vbp` files: Eduardo A. Morcillo, Microsoft Corporation.
Third-party attribution: Eduardo A. Morcillo (Edanmo). See `THIRD_PARTY_NOTICES.md`.

## License

Third-party code remains under its original terms (or none, where none were supplied). See `THIRD_PARTY_NOTICES.md`. Do not treat this tree as VaderConsulting original MIT-licensed work.
