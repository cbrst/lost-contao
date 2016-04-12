<p style="text-align: center">
	<img src="http://crshd.github.io/lost-contao/images/lost-contao.png">
</p>

---

This is an excercise in integrating Lost Grid's flexy goodness into Contao as a drop-in replacement for the built-in grid.

> Heavily WIP.<br>
> Would not recommend for production use.<br>

---

## Usage

### Compatibility

It's mostly consistent at what it does. Not 100% compatible. You'll have to adjust your style a bit.

##### Columns
LostContao tries to comply with Contao Grid's usage. We're based on 12 columns, and elements can span multiple columns based on the `grid1` through `grid12` classes.

##### Offsets
Offset can be defined with the `offset1` through `offset11` classes.

##### Cycle
Adding the class `last` (automatically added by Contao to the last element &ndash; see what we did there?) does a `lost-cycle`, i.e. removes the margin-right.

### Utils

We've added some additional classes for commonly used functions.

##### `.flex-column`
Switches `flex-flow` to `column wrap` instead of `row wrap`

---

## "Thank You"s

- **Leo Feyer** and the [team around **Contao**](https://contao.org/de/ueber-contao.html)
- **Peter Ramsing** for [lost](https://github.com/peterramsing/lost)
