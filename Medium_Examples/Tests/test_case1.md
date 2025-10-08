#Test Case – Cart Behavior with Multiple Products

## Test Case ID
TC_CART_001

## Title
Cart fails to update quantities with 3 different products (pre-fix) and works correctly after development fix

## Priority
High

## Preconditions
- User is logged in
- Product catalog is available
- Cart is empty before starting

## Test Steps

### 🔹 Pre-Fix Test
1. Add 3 different products to the cart
2. Try to increase the quantity of any product
3. Try to decrease the quantity of any product
4. Try to remove a product from the cart

### 🔹 Post-Fix Test
1. Repeat the same steps after development fix
2. Verify that quantity can be increased above 3
3. Verify that products can be removed correctly

## Test Data
| Product Name       | Quantity |
|--------------------|----------|
| Sauce Labs Backpack | 1        |
| Sauce Labs Bike Light | 1     |
| Sauce Labs Bolt T-Shirt | 1   |

## Expected Results
- Pre-Fix: Cart fails to update quantities or remove items when 3 products are present
- Post-Fix: Cart allows quantity updates and item removal without issues

## Actual Results

### 🔹 Pre-Fix
- Cart blocked quantity changes and removal
- No error message shown
- Issue confirmed

### 🔹 Post-Fix
- Cart allowed quantity updates above 3
- Products could be removed
- Behavior matched expected results

## Evidence

- 📸 Screenshot before fix: `../Evidence/Screenshots/TEST1_first.png`
- 🎥 Video recording of issue: `../Evidence/Prueba_video.mp4`
- 📸 Screenshot after fix: `../Evidence/Screenshots/TEST1_Pos.png`

## Status
**Passed after fix**

## Notes
> The issue was confirmed during manual testing and recorded via video.  
> After applying the development fix, the cart behavior was validated successfully.