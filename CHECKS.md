# M10 checks

## Case 31 calculations

- The portfolio workbook matches the supplied original workbook byte for byte.
- All numeric values and missing positions match the prepared SPSS file.
- The prepared file contains 128 rows and 54 columns.
- The employee average column matches the per-record mean of q3 through q6.
- Employee average: 4.205078125, displayed as 4.21 out of 5; all 128 records complete.
- Overall rating: 102 good/excellent ratings out of 121 valid answers, displayed as 84.3%; seven missing answers excluded.
- Current loan: 58 yes responses out of 128 yes/no answers, displayed as 45.3%.
- All 14 awareness items have 128 valid answers. Their three response counts sum to 128 for each service.
- Awareness recodes match the preparation file: 1 unaware, 2 aware but not used, 3 aware and used.
- Savings-rate n = 118; borrowing-rate n = 107. These distributions use their own valid-answer denominators.
- The original q8 SPSS variable label says statement frequency, but the instructor preparation script identifies q8r as fund borrowing rates. The dashboard follows that corrected label.
- Rate perception runs from very low to very high; higher borrowing-rate scores are not treated as greater satisfaction.
- Prepared recoded columns are not reversed again. Missing answers are not replaced by zero.
- The printed case's 123 usable returns and the file's 128 records are kept distinct. No response rate is calculated.

## Assignment pages

- Home: bio, photo, career goals, skills, education, and experience.
- Dashboard portal: clear link to the separate Case 31 dashboard.
- Dashboard: three pages, four value boxes, charts, tables, tabs, sources, definitions, and missing-answer notes.
- CSS/SCSS: live note/card examples, code examples, variables, selectors, nesting, and links to documentation.
- Listings: three actual linked entries, skill categories, and an explanation of the YAML settings.
- Website configuration: four top-level navigation links; all six website QMDs explicitly included.
- Source data and attribution are included; the scanned case and instructor solutions are not redistributed.

## Rendering and browser checks

The full website rendered successfully with Quarto 1.8.27 and R 4.3.3.
The dashboard uses `format: dashboard` and displays styled value boxes rather than raw R lists.
The browser checks covered the photo, local assets, portal link, dashboard page navigation,
rate chart tab, and Listings R category. Desktop and narrow-screen layouts were inspected.
Wide dashboard tables scroll inside their cards on a narrow screen.

## Still required before submission

The user has not published yet. Create the GitHub repository, publish `docs/`
through GitHub Pages, and open both URLs in the submission HTML to confirm
that they work. The submission links are prefilled for `Sheilaaa0312/M10-Hands-on-Practice`.
If a different repository name is used, edit both URLs in the QMD and render it again.
