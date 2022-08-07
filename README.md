# EXCEL-Tracing-Precedent-and-dependent-cells
Trace the precedents for various functions.
    Select cell F9 and examine the formula.
    Precedent cells (cells that feed into) this formula include:
    Range B2:B51 in the Pay Data worksheet.
    Cell C6 in this worksheet.
    Salary, a named range.
    Select Formulas→Trace Precedents.
    Lines are shown to represent the cells that feed into this formula. Cell C6 is in the same worksheet, so the blue line directly connects cell F9 to it. The other precedents are located in a different workbook, so they are represented by a black, dashed line connected to a worksheet icon.
    Double-click the blue trace arrow.
    Cell C6 is selected.
    Double-click the black, dashed-line arrow.
    There are two precedents in other worksheets. The Go To dialog box is shown so you can select which one you want to go to.
    In the Go to section, select the second reference to [My Employees.xlsx]Pay Data!$D$2:$D$51.
    Select OK.
    Observe that the range of D2:D51 is selected on the Pay Data worksheet.
Remove the precedent arrows.
    Select the Employees worksheet, and then select cell F9.
    Select Formulas→Remove Arrows→Remove Precedent Arrows.
Trace all dependents for the Employee ID.
    Select cell C3 and then select Formulas→Trace Dependents.
    Select Trace Dependents again.
    Observe that many formulas are dependent on Employee ID.
    Select Remove Arrows (the button, not its drop-down arrow).
    This command removes arrows for both precedents and dependents, if present.

