[![Stand With Palestine](https://raw.githubusercontent.com/TheBSD/StandWithPalestine/main/banner-no-action.svg)](https://TheBSD.github.io/StandWithPalestine/)

# Blazor-Components

These component you can use them up and running..



```cs
// Call ModalDialog 
<ModalDialog Title='AreYouSure'
     Text='ConfirmDelete"'
     OnClose="@OnDialogClose"
     DialogType="ModalDialogType.DeleteCancel">
</ModalDialog>
```
        

```cs
// Call ToastDialog 
<ToastDialog IsSuccessed='true'
      ToastMessage='toastMessage'>
</ToastDialog>
```
