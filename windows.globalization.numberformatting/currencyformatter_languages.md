---
-api-id: P:Windows.Globalization.NumberFormatting.CurrencyFormatter.Languages
-api-type: winrt property
---

<!-- Property syntax
public Windows.Foundation.Collections.IVectorView<string> Languages { get; }
-->

# Windows.Globalization.NumberFormatting.CurrencyFormatter.Languages

## -description
Gets the priority list of language identifiers that is used when formatting and parsing currency values.

## -property-value
The priority list of language identifiers.

**Starting in :** Language tags can support Unicode extensions. See the Remarks for the [CurrencyFormatter(String, IIterable(String), String)](currencyformatter_currencyformatter_1781948400.md) constructor.

## -remarks
If your app passes language tags from this class to any [National Language Support](https://msdn.microsoft.com/library/7a548074-0782-45e1-8051-80c3b9d81885) functions, it must first convert the tags by calling [ResolveLocaleName](https://msdn.microsoft.com/library/99264b22-3fb5-47e2-b0b9-42a6768e67c1).

## -examples

## -see-also
