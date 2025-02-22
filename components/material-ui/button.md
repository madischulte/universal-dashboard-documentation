# Button

## Contained

```text
New-UDMuButton -Text 'Submit' -Variant contained
```

![Contained Button](../../.gitbook/assets/image%20%2843%29.png)

## Flat

```text
New-UDMuButton -Text 'Submit' -Variant flat
```

![Flat button](../../.gitbook/assets/button.gif)

## Outlined

```text
New-UDMuButton -Text 'Submit' -Variant outlined
```

![Outlined Button](../../.gitbook/assets/image%20%2836%29.png)

## Icons

```text
New-UDMuButton -Text 'Buy' -Variant contained -Icon (New-UDMuIcon -Icon bitcoin -Size '4x')
```

![Icon Button](../../.gitbook/assets/image%20%2856%29.png)

## Full Width

```text
New-UDMuButton -Text 'Submit' -Variant contained -FullWidth
```

![Full Width Button](../../.gitbook/assets/image%20%2844%29.png)

## OnClick Handler

```text
New-UDMuButton -Text 'Submit' -Variant contained -OnClick { 
    Show-UDToast -Message "You clicked me!" -Position topLeft
}
```

![Button onClick Handler](../../.gitbook/assets/buttononclick.gif)

## Custom Colors

```text
New-UDMuButton -Text 'Submit' -Variant contained -Style @{ backgroundColor = "blue"; color = "white" }
```

![Colored Button](../../.gitbook/assets/image%20%2833%29.png)

