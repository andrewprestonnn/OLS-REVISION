OLS regression revision lab

An interactive, mobile-friendly illustration of ordinary least squares. All styles and JavaScript are embedded in `index.html`: no installation, build step, network access, or external dependencies.

## Use offline

Download `index.html` and open it in a modern browser. Drag dots with a mouse or touch. You can also Tab to a dot and use arrow keys; hold Shift for larger steps. Choose an example, add a month, or remove a selected point. At least two points are retained.

The line, equation, residuals, SSR, R², and data table update immediately. Enable **Try your own line** to compare a manual line with the OLS minimum. Reset restores the selected example. Changes are held in memory and are discarded on reload.

Statistical interpretation

X is market return and Y is stock return, both in percent. The slope is a change in stock return in percentage points for a one percentage point increase in market return. The intercept is the predicted stock return at zero market return.

OLS fits an intercept and slope by minimising the sum of squared vertical residuals. SSR is measured in percentage points squared. R² is 1 − SSR/TSS and is undefined when Y has no variation. If all X values are equal, the slope is not identifiable; the page reports this and draws a mean-Y line as one minimum-error solution.

The data are illustrative, not real market observations. Fit does not establish causation or validate statistical inference. The page does not calculate standard errors or t-tests.
