---
title: "Functions"
echo: false
#jupyter: python3
section-divs: false
keep-md: true
---


::: {.cell}

:::


## Placeholder

All the functions are below to show they can be pulled from the `.rd` files,
but ideally we'd replace this page with a search.

## Function metrics

There are 344  functions exported 
from the 7 packages in this package family.


::: {.cell}
::: {.cell-output-display}
Table: Functions present in the packages

|package               | Exported| Internal|
|:---------------------|--------:|--------:|
|formatters            |       33|       NA|
|nestcolor             |        2|       NA|
|rtables               |      106|       NA|
|teal                  |       22|       29|
|teal.modules.clinical |       56|       52|
|teal.modules.general  |       17|       20|
|tern                  |      108|       53|
:::
:::


## Functions



### [teal](https://insightsengineering.github.io/teal) 


**bookmarkableShinyApp()**: Make a Shiny UI function bookmarkable

**default_filter()**: Refers the default filter state

**example_module()**: An example 
list("teal")
 module

**get_rcode_srv()**: Server part of get R code module

**get_rcode_ui()**: Ui part of get R code module

**get_rcode()**: Returns R Code from a teal module

**init()**: Create the Server and UI Function For the Shiny App

**log_app_usage()**: Teal Application Usage Logging.

**module()**: Creates a 
list("teal_module")
 object.

**modules()**: Creates a 
list("teal_modules")
 object.

**reporter_previewer_module()**: Create a 
list("teal")
 module for previewing a report

**root_modules()**: Deprecated: Creates the root modules container

**show_rcode_modal()**: Show R Code Modal

**srv_teal_with_splash()**: Server function that loads the data through reactive loading and then delegates

to 
list(list("srv_teal()"))
.

**ui_teal_with_splash()**: UI to show a splash screen in the beginning, then delegate to 
list(list("srv_teal()"))

**validate_has_data()**: Validate that dataset has a minimum number of observations

**validate_has_elements()**: Validates that vector has length greater than 0

**validate_has_variable()**: Validates that dataset contains specific variable

**validate_in()**: Validates that vector includes all expected values

**validate_n_levels()**: Validate that variables has expected number of levels

**validate_no_intersection()**: Validates no intersection between two vectors

**validate_one_row_per_id()**: Validate that dataset has unique rows for key variables

### [teal.modules.general](https://insightsengineering.github.io/tern.modules.general) 


**add_facet_labels()**: Add axis labels that show facetting variable

**get_scatterplotmatrix_stats()**: Get stats for x-y pairs in scatterplot matrix

**tm_a_pca()**: Principal component analysis module

**tm_a_regression()**: Scatterplot and Regression Model

**tm_data_table()**: Data Table Viewer Teal Module

**tm_file_viewer()**: File Viewer Teal Module

**tm_front_page()**: Front page module

**tm_g_association()**: Stack Plots of variables and show association with reference variable

**tm_g_bivariate()**: Univariate and bivariate visualizations

**tm_g_distribution()**: Distribution Module

**tm_g_response()**: Response Plots

**tm_g_scatterplot()**: Create a simple scatterplot

**tm_g_scatterplotmatrix()**: Create a scatterplot matrix

**tm_missing_data()**: Missing data module

**tm_outliers()**: Outliers Module

**tm_t_crosstable()**: Create a simple cross-table

**tm_variable_browser()**: Variable Browser Teal Module

### [teal.modules.clinical](https://insightsengineering.github.io/teal.modules.clinical) 


**add_expr()**: Expression List

**bracket_expr()**: Expressions in Brackets

**call_concatenate()**: Concatenate expressions via a binary operator

**clean_description()**: Clean a categorical variable descriptions

**color_lab_values()**: Mapping function for Laboratory Table

**column_annotation_label()**: Get full label, useful for annotating plots

**cs_to_des_filter()**: Convert choices_selected to data_extract_spec with only filter_spec

**cs_to_des_select()**: Convert choices_selected to data_extract_spec with only select_spec

**cs_to_filter_spec()**: Convert choices_selected to filter_spec

**cs_to_select_spec()**: Convert choices_selected to select_spec

**extract_input()**: Extracts html id for data_extract_ui

**get_var_labels()**: Get variable labels

**h_concat_expr()**: Expression Deparsing

**is.cs_or_des()**: Whether object is of class 
list(list("teal.transform::choices_selected()"))
 or 
list(list("teal.transform::data_extract_spec()"))

**pipe_expr()**: Expressions as a Pipeline

**prepare_arm_levels()**: Expression: Prepare Arm Levels

**prepare_arm()**: Expression: Arm Preparation

**split_choices()**: Split 
list("choices_selected")
 objects with interactions into

their component variables

**split_col_expr()**: Split-Column Expression

**split_interactions()**: Split interaction terms into their component variables

**styled_expr()**: Styled Code Printing

**tm_a_mmrm()**: Teal Module: Teal module for Mixed Model Repeated Measurements (MMRM) analysis

**tm_g_barchart_simple()**: Simple barchart plot that shows counts per category.

**tm_g_ci()**: Teal Module: Confidence Interval Plot (
list("CIG01")
)

**tm_g_forest_rsp()**: Teal Module: Forest Response Plot teal module

**tm_g_forest_tte()**: Teal Module: Forest Survival Plot teal Module

**tm_g_ipp()**: Teal Module: Individual Patient Plot

**tm_g_km()**: Teal Module: Kaplan-Meier

**tm_g_lineplot()**: Teal Module: Line Plot

**tm_g_pp_adverse_events()**: Teal Module: Patient Profile Adverse Events Teal Module

**tm_g_pp_patient_timeline()**: Teal Module: Patient Profile Timeline Teal Module

**tm_g_pp_therapy()**: Teal Module: Patient Profile Therapy Teal Module

**tm_g_pp_vitals()**: Teal Module: Patient Profile Vitals Teal Module

**tm_t_abnormality_by_worst_grade()**: Teal Module: Laboratory test results with highest grade post-baseline

**tm_t_abnormality()**: Teal Module: Abnormality Summary Table

**tm_t_ancova()**: Teal Module: ANCOVA Teal Module

**tm_t_binary_outcome()**: Teal Module: Binary Outcome Table

**tm_t_coxreg()**: Teal Module: Cox Regression Model

**tm_t_events_by_grade()**: Teal Module: Events by Grade

**tm_t_events_patyear()**: Teal module: Event rates adjusted for patient-years

**tm_t_events_summary()**: Teal Module: Adverse Events Summary

**tm_t_events()**: Teal Module: Events by Term

**tm_t_exposure()**: Teal module: Exposure Table for Risk management plan

**tm_t_logistic()**: Teal Module: Logistic Regression

**tm_t_mult_events()**: Teal Module: Multiple Events by Term

**tm_t_pp_basic_info()**: Teal Module: Patient Profile Basic Info Teal Module

**tm_t_pp_laboratory()**: Teal Module: Patient Profile Laboratory Teal Module

**tm_t_pp_medical_history()**: Teal Module: Patient Medical History Teal Module

**tm_t_pp_prior_medication()**: Teal Module: Patient Prior Medication Teal Module

**tm_t_shift_by_arm_by_worst()**: Teal Module: Shift by Arm by Worst

**tm_t_shift_by_arm()**: Teal Module: Shift by Arm

**tm_t_shift_by_grade()**: Teal Module: Grade Summary Table

**tm_t_smq()**: Teal Module: 
list("SMQ")
 Table

**tm_t_summary_by()**: Teal Module: Summarize Variables by Row Groups Module

**tm_t_summary()**: Teal Module: Summary of Variables

**tm_t_tte()**: Teal Module: Time To Event Table Teal Module

### [tern](https://insightsengineering.github.io/tern) 


**add_footnotes<-()**: Add Footnotes

**add_rowcounts()**: Layout Creating Function to Add Row Total Counts

**aesi_label()**: Labels for Adverse Event Baskets

**append_varlabels()**: Add Variable Labels to Top Left Corner in Table

**as.rtable()**: Convert to 
list("rtable")

**color_palette()**: Deprecated by 
list("nestcolor::color_palette")
: Color Palettes Used in NEST

**combination_function()**: Combination Functions Class

**combine_groups()**: Reference and Treatment Group Combination

**combine_levels()**: Combine Factor Levels

**compare_variables()**: Compare Variables Between Groups

**control_coxph()**: Control Function for 
list("CoxPH")
 Model

**control_coxreg()**: Controls for Cox regression

**control_incidence_rate()**: Control function for incidence rate

**control_lineplot_vars()**: Control Function for g_lineplot Function

**control_logistic()**: Control Function for Logistic Regression Model Fitting

**control_step()**: Control Function for Subgroup Treatment Effect Pattern (STEP) Calculations

**control_summarize_vars()**: Control Function for Descriptive Statistics

**control_surv_time()**: Control Function for 
list("survfit")
 Model for Survival Time

**control_surv_timepoint()**: Control Function for 
list("survfit")
 Model for Patient's Survival Rate at time point

**count_occurrences_by_grade()**: Occurrence Counts by Grade

**count_occurrences()**: Occurrence Counts

**count_patients_with_event()**: Count the Number of Patients with a Particular Event

**count_values_funs()**: Counting Specific Values

**cox_regression_inter()**: Cox Regression Helper: Interactions

**cox_regression()**: Cox Proportional Hazards Regression

**cut_quantile_bins()**: Cutting Numeric Vector into Empirical Quantile Bins

**d_count_cumulative()**: Description of Cumulative Count

**d_pkparam()**: Generate PK reference dataset

**d_proportion()**: Description of the Proportion Summary

**d_rsp_subgroups_colvars()**: Labels for Column Variables in Binary Response by Subgroup Table

**d_survival_subgroups_colvars()**: Labels for Column Variables in Survival Duration by Subgroup Table

**d_test_proportion_diff()**: Description of the Difference Test Between Two Proportions

**day2month()**: Conversion of Days to Months

**decorate_grob_set()**: Decorate Set of 
list("grobs")
 and Add Page Numbering

**decorate_grob()**: Add Titles, Footnotes, Page Number, and a Bounding Box to a Grid Grob

**df_explicit_na()**: Encode Categorical Missing Values in a Data Frame

**draw_grob()**: Draw 
list("grob")

**estimate_multinomial_rsp()**: Estimation of Proportions per Level of Factor

**estimate_proportions()**: Estimation of Proportions

**explicit_na()**: Missing Data

**extreme_format()**: Formatting Extreme Values

**f_conf_level()**: Utility function to create label for confidence interval

**fct_collapse_only()**: Collapsing of Factor Levels and Keeping Only Those New Group Levels

**fct_discard()**: Discard Certain Levels from a Factor

**fct_explicit_na_if()**: Insertion of Explicit Missings in a Factor

**fit_rsp_step()**: Subgroup Treatment Effect Pattern (STEP) Fit for Binary (Response) Outcome

**fit_survival_step()**: Subgroup Treatment Effect Pattern (STEP) Fit for Survival Outcome

**footnotes()**: Retrieve Footnotes

**footnotes<-()**: Assign Footnotes

**format_count_fraction()**: Formatting Count and Fraction

**format_fraction_threshold()**: Formatting Fraction with Lower Threshold

**format_fraction()**: Formatting Fraction and Percentage

**formatting_functions()**: Additional Formatting Functions

**g_forest()**: Create a Forest Plot based on a Table

**g_km()**: Kaplan-Meier Plot

**g_lineplot()**: Line plot with the optional table

**g_step()**: Create a STEP Graph

**g_waterfall()**: Horizontal Waterfall Plot

**get_smooths()**: Smooth Function with Optional Grouping

**h_adsl_adlb_merge_using_worst_flag()**: Helper Function for Deriving Analysis Datasets for LBT13 and LBT14

**h_col_indices()**: Obtain Column Indices

**h_data_plot()**: Helper function: tidy survival fit

**h_decompose_gg()**: list("ggplot")
 Decomposition

**h_format_row()**: Helper function to get the right formatting in the optional table in g_lineplot.

**h_ggkm()**: Helper function: KM plot

**h_grob_coxph()**: Helper Function: CoxPH Grob

**h_grob_median_surv()**: Helper Function: Survival Estimation Grob

**h_grob_tbl_at_risk()**: Helper: Patient-at-Risk Grobs

**h_grob_y_annot()**: Helper: Grid Object with y-axis Annotation

**h_km_layout()**: Helper: KM Layout

**h_map_for_count_abnormal()**: Helper Function to create a map dataframe that can be used in 
list("trim_levels_to_map")
 split function.

**h_pkparam_sort()**: Sort 
list("PK PARAM")
 variable

**h_response_biomarkers_subgroups()**: Helper Functions for Tabulating Biomarker Effects on Binary Response by Subgroup

**h_response_subgroups()**: Helper Functions for Tabulating Binary Response by Subgroup

**h_split_by_subgroups()**: Split Dataframe by Subgroups

**h_split_param()**: Split parameters

**h_stack_by_baskets()**: Helper Function to create a new 
list("SMQ")
 variable in 
list("ADAE")
 by stacking

list("SMQ")
 and/or 
list("CQ")
 records.

**h_step()**: Helper Functions for Subgroup Treatment Effect Pattern (STEP) Calculations

**h_survival_biomarkers_subgroups()**: Helper Functions for Tabulating Biomarker Effects on Survival by Subgroup

**h_survival_duration_subgroups()**: Helper Functions for Tabulating Survival Duration by Subgroup

**h_tab_one_biomarker()**: Helper Function for Tabulation of a Single Biomarker Result

**h_tbl_coxph_pairwise()**: Helper Function: Pairwise CoxPH table

**h_tbl_median_surv()**: Helper Function: Survival Estimations

**h_xticks()**: Helper function: x tick positions

**individual_patient_plot()**: Individual Patient Plots

**kaplan_meier()**: Kaplan-Meier Plot

**logistic_regression()**: Multi-variable logistic regression table

**month2day()**: Conversion of Months to Days

**odds_ratio()**: Odds Ratio Estimation

**pairwise()**: Pairwise formula special term

**prop_diff()**: Proportion Difference

**response_biomarkers_subgroups()**: Tabulate Biomarker Effects on Binary Response by Subgroup

**s_cox_univariate()**: Cox regression including a single covariate - summarized results

**sas_na()**: Convert Strings to 
list("NA")

**score_occurrences()**: Occurrence Table Sorting

**split_cols_by_groups()**: Split Columns by Groups of Levels

**stack_grobs()**: Stack Multiple Grobs

**stat_mean_ci()**: Confidence Interval for Mean

**stat_median_ci()**: Confidence Interval for Median

**summarize_colvars()**: Summarize Variables in Columns

**summarize_num_patients()**: Number of patients

**summarize_variables()**: Summarize Variables

**summary_in_cols()**: Summary numeric variables in columns

**survival_biomarkers_subgroups()**: Tabulate Biomarker Effects on Survival by Subgroup

**tern-package()**: tern Package

**to_n()**: Replicate Entries of a Vector if Required

**to_string_matrix()**: Convert Table into Matrix of Strings

**univariate()**: Univariate formula special term

### [nestcolor](https://insightsengineering.github.io/nestcolor) 


**color_palette()**: Color Palettes Used in NEST

**theme_nest()**: Returns a custom 
list("NEST")
 
list("ggplot2")
 theme

### [rtables](https://roche.github.io/rtables/) 


**[<-,VTableTree,ANY,ANY,list-method()**: retrieve and assign elements of a TableTree

**add_colcounts()**: Add the column population counts to the header

**add_existing_table()**: Add an already calculated table to the layout

**add_overall_col()**: Add Overall Column

**add_overall_level()**: Add an virtual 'overall' level to split

**all_zero_or_na()**: Trimming and Pruning Criteria

**analyze_colvars()**: Generate Rows Analyzing Different Variables Across Columns

**analyze()**: Generate Rows Analyzing Variables Across Columns

**AnalyzeVarSplit()**: Define a subset tabulation/analysis

**append_topleft()**: Append a description to the 'top-left' materials for the layout

**as_html()**: Convert an 
list("rtable")
 object to a 
list("shiny.tag")
 html object

**as.vector,TableRow-method()**: convert to a vector

**basic_table()**: Layout with 1 column and zero rows

**build_table()**: Create a table from a layout and data

**cbind_rtables()**: cbind two rtables

**cell_values()**: Retrieve cell values by row and column path

**CellValue()**: Cell Value constructor

**clayout()**: Column information/structure accessors

**clear_indent_mods()**: Clear All Indent Mods from a Table

**collect_leaves()**: Collect leaves of a table tree

**compare_rtables()**: Compare two rtables

**compat_args()**: Compatability Arg Conventions

**constr_args()**: Constructor Arg Conventions

**cont_n_allcols()**: Score functions for sorting TableTrees

**content_table()**: Retrieve or set Content Table from a TableTree

**custom_split_funs()**: Custom Split Functions

**df_to_tt()**: Create ElementaryTable from data.frame

**do_base_split()**: Apply Basic Split (For Use In Custom Split Functions)

**ElementaryTable-class()**: TableTree classes

**EmptyColInfo()**: Empty table, column, split objects

**export_as_pdf()**: Export as PDF

**export_as_tsv()**: Create Enriched flat value table with paths

**export_as_txt()**: Export as plain text with page break symbol

**format_rcell()**: Format rcell

**gen_args()**: General Argument Conventions

**get_formatted_cells()**: get formatted cells

**head()**: Head and tail methods

**horizontal_sep()**: Access or recursively set header-body separator for tables

**in_rows()**: Create multiple rows in analysis or summary functions

**indent_string()**: Indent Strings

**indent()**: Change indentation of all rrows in an rtable

**insert_row_at_path()**: Insert Row at Path

**insert_rrow()**: [DEPRECATED] insert rrows at (before) a specific location

**InstantiatedColumnInfo-class()**: InstantiatedColumnInfo

**internal_methods()**: combine SplitVector objects

**is_rtable()**: Check if an object is a valid rtable

**label_at_path()**: Label at Path

**LabelRow()**: Row classes and constructors

**length,CellValue-method()**: Length of a Cell value

**list_wrap_x()**: Returns a function that coerces the return values of f to a list

**lyt_args()**: Layouting Function Arg Conventions

**main_title,VTitleFooter-method()**: Titles and Footers

**make_afun()**: Create custom analysis function wrapping existing function

**make_row_df()**: Column Layout Summary

**manual_cols()**: Manual column declaration

**ManualSplit()**: Manually defined split

**matrix_form,VTableTree-method()**: Transform rtable to a list of matrices which can be used for outputting

**MultiVarSplit()**: Split between two or more different variables

**names,VTableNodeInfo-method()**: Names of a TableTree

**no_colinfo()**: Exported for use in tern

**nrow,VTableTree-method()**: Table Dimensions

**obj_avar()**: Row attribute accessors

**obj_name,VNodeInfo-method()**: Label, Name and Format accessor generics

**pag_tt_indices()**: Pagination of a TableTree

**path_enriched_df()**: Transform TableTree object to Path-Enriched data.frame

**prune_table()**: Recursively prune a TableTree

**rbindl_rtables()**: rbind TableTree and related objects

**rcell()**: Cell value constructors

**remove_split_levels()**: Split functions

**rheader()**: Create a header

**row_footnotes()**: Referential Footnote Accessors

**row_paths_summary()**: Print Row/Col Paths Summary

**row_paths()**: Return List with Table Row/Col Paths

**rrow()**: row

**rrowl()**: rrowl

**rtable()**: Create a Table

**rtables_aligns()**: Currently supported cell value alignments

**select_all_levels()**: Add Combination Levels to split

**sf_args()**: Split Function Arg Conventions

**simple_analysis()**: Default tabulation

**sort_at_path()**: Sort substructure of a TableTree at a particular Path in the Tree.

**spl_context_to_disp_path()**: Translate spl_context to Path for display in error messages

**spl_context()**: .spl_context within analysis and split functions

**split_cols_by_cuts()**: Split on static or dynamic cuts of the data

**split_cols_by_multivar()**: Associate Multiple Variables with Columns

**split_cols_by()**: Declaring a column-split based on levels of a variable

**split_rows_by()**: Add Rows according to levels of a variable

**summarize_row_groups()**: Add a content row of summary counts

**summarize_rows()**: summarize_rows

**table_shell()**: Table shells

**table_structure()**: Summarize Table

**top_left()**: Top Left Material (Experimental)

**tostring()**: Convert an 
list("rtable")
 object to a string

**tree_children()**: Retrieve or set the direct children of a Tree-style object

**trim_levels_to_map()**: Trim Levels to map

**trim_rows()**: Trim rows from a populated table without regard for table structure

**trim_zero_rows()**: Trim Zero Rows

**tt_at_path()**: Get or set table elements at specified path

**tt_to_flextable()**: Create a FlexTable object representing an rtables TableTree

**update_ref_indexing()**: Update footnote indexes on a built table

**value_formats()**: Value Formats

**VarLevelSplit-class()**: Split on levels within a variable

**vars_in_layout()**: List Variables required by a pre-data table layout

**VarStaticCutSplit-class()**: Splits for cutting by values of a numeric variable

**Viewer()**: Display an 
list(list("rtable"))
 object in the Viewer pane in RStudio or in a

browser

**vpaginate_table()**: Deprecated - vertically paginate table

### [formatters](https://insightsengineering.github.io/formatters/) 


**basic_matrix_form()**: Create spoof matrix form from a data.frame

**basic_pagdf()**: Basic/spoof pagination info dataframe

**default_hsep()**: Default horizontal Separator

**divider_height()**: Divider Height

**DM()**: DM data

**ex_adsl()**: Simulated CDISC Alike Data for Examples

**format_value()**: Converts a (possibly compound) value into a string using the 
list("format")
 information

**ifnotlen0()**: '%||%' If length-0 alternative operator

**is_valid_format()**: Check if a format is supported

**is.wholenumber()**: is.wholenumber

**lab_name()**: Label, Name and Format accessor generics

**list_valid_format_labels()**: List with currently support 'xx' style format labels grouped by 1d, 2d and 3d

**main_title()**: General title/footer accessors

**make_row_df()**: Make row and column layout summary data.frames for use during pagination

**matrix_form()**: Transform rtable to a list of matrices which can be used for outputting

**MatrixPrintForm()**: Matrix Print Form - Intermediate Representation for ASCII Table Printing

**nlines()**: Number of lines required to print a value

**padstr()**: Pad a string and align within string

**pag_indices_inner()**: Find Pagination Indices From Pagination Info Dataframe

**pagdfrow()**: Create row of pagination data frame

**print,ANY-method()**: Print

**propose_column_widths()**: Propose Column Widths based on an object's `MatrixPrintForm` form

**round_fmt()**: Round and prepare a value for display

**spans_to_viscell()**: Transform vectors of spans (with dupblication) to Visibility vector

**spread_integer()**: spread x into len elements

**sprintf_format()**: Specify text format via a sprintf format string

**toString()**: toString

**var_labels_remove()**: Remove Variable Labels of a 
list("data.frame")

**var_labels()**: Get Label Attributes of Variables in a 
list("data.frame")

**var_labels<-()**: Set Label Attributes of All Variables in a 
list("data.frame")

**var_relabel()**: Copy and Change Variable Labels of a 
list("data.frame")

**vert_pag_indices()**: Find Column Indicies for Vertical Pagination

**with_label()**: Return an object with a label attribute


## Internal non-exported functions



### teal 


**.log()**
A logging function

**append_module()**
Function which appends a teal_module onto the children of a teal_modules object

**filter_calls_module()**
Dummy module to show the filter calls generated by the right encoding panel

**fold_lines()**
Fixed line width folding

**get_client_timezone()**
Get Client Timezone

**get_datasets_code()**
Get datasets code

**get_dummy_cdisc_data()**
Get dummy CDISC data

**get_dummy_datasets()**
Get a dummy 
list("datasets")
 object with 
list("ADSL")
 data, useful in the examples

**get_dummy_filter()**
Get dummy filter states to apply initially

**get_dummy_modules()**
Get dummy modules

**get_rcode_header()**
Generates header text for analysis items

**get_rcode_libraries()**
Generates library calls from current session info

**include_css_files()**
Include 
list("CSS")
 files from 
list("/inst/css/")
 package directory to application header

**include_js_files()**
Include 
list("JS")
 files from 
list("/inst/js/")
 package directory to application header

**include_teal_css_js()**
Code to include teal CSS and Javascript files

**is_arg_used()**
Does the object make use of the 
list("arg")

**line_pkg_log()**
Package metadata to add to log file

**line_usage_log()**
app usage data fields to add to log file

**modules_depth()**
Get module depth

**pad()**
Pads a string

**reexports()**
Objects exported from other packages

**run_js_files()**
Run 
list("JS")
 file from 
list("/inst/js/")
 package directory

**srv_nested_tabs()**
Server function that returns currently active module

**srv_tabs_with_filters()**
Server function

**srv_teal()**
Server function corresponding to teal

**teal-package()**
teal: Interactive Exploration of Clinical Trials Data

**ui_nested_tabs()**
Create a UI of nested tabs of 
list("teal_modules")

**ui_tabs_with_filters()**
Add right filter panel into each of the top-level 
list("teal_modules")
 UIs.

**ui_teal()**
Teal app UI

### teal.modules.general 


**call_fun_dots()**
Call a function with a character vector for the 
list("...")
 argument

**create_sparklines()**
S3 generic for 
list("sparkline")
 widget HTML

**establish_updating_selection()**
Creates observers updating the currently selected column

**extract_input()**
Extract html id for data_extract_ui

**get_datanames_selected()**
a tool for ui and server for getting datanames taking into account the datasets_selected vector

**get_var_description()**
Returns a short variable description.

**include_css_files()**
Include 
list("CSS")
 files from 
list("/inst/css/")
 package directory to application header

**plot_var_summary()**
Plot variable

**remove_outliers_from()**
Removes the outlier observation from an array

**render_single_tab()**
Renders a single tab in the left-hand side tabset panel

**render_tab_header()**
Renders the text headlining a single tab in the left-hand side tabset panel

**render_tab_table()**
Renders the table for a single dataset in the left-hand side tabset panel

**render_tabset_panel_content()**
Renders the left-hand side 
list("tabset")
 panel of the module

**shared_params()**
Shared Parameters

**teal.modules.general()**
teal.modules.general: General modules to add to a teal application

**validate_input()**
Validates the variable browser inputs

**var_missings_info()**
Summarizes missings occurrence

**var_summary_table()**
Summarizes variable

**variable_type_icons()**
Get icons to represent variable types in dataset

**varname_w_label()**
Get variable name with label

### teal.modules.clinical 


**arm_ref_comp_observer()**
Observer for Treatment reference variable

**as_num()**
Parse text input to numeric vector

**check_arm_ref_comp()**
Check if the Treatment variable is reference or compare

**control_tte()**
Control Function for Time-to-Event Teal Module

**dyn_assertion()**
Dynamic assertion

**facet_grid_formula()**
Facetting formula 
list("x_facet ~ y_facet")

**get_g_forest_obj_var_name()**
Utility function for extracting paramcd for forest plots

**get_paramcd_label()**
Extract the associated param value for paramcd

**make_barchart_simple_call()**
list("ggplot2")
 call to generate simple barchart

**module_arguments()**
Standard Module Arguments

**substitute_names()**
Substitute Names in a Quoted Expression

**substitute_q()**
Substitute in Quoted Expressions

**teal.modules.clinical()**
Teal Modules for Standard Clinical Outputs

**template_abnormality_by_worst_grade()**
Template: Laboratory test results with highest grade post-baseline

**template_abnormality()**
Template: Abnormality Summary Table

**template_adverse_events()**
Template: Adverse Events Tab

**template_ancova()**
Template: ANCOVA summary

**template_arguments()**
Standard Template Arguments

**template_basic_info()**
Template: Basic Info

**template_binary_outcome()**
Template: Binary Outcome

**template_coxreg_m()**
Template: Cox Regression Multivariate

**template_coxreg_u()**
Template: Cox Regression Univariate

**template_events_by_grade()**
Template: Events by Grade

**template_events_col_by_grade()**
Template: Adverse Events grouped by Grade with threshold

**template_events_patyear()**
Template: Event rates adjusted for patient-years

**template_events_summary()**
Template: Adverse Events Summary

**template_events()**
Template: Events by Term

**template_exposure()**
Template: Exposure Table for Risk management plan

**template_fit_mmrm()**
Template: Mixed Model Repeated Measurements (MMRM) analysis

**template_forest_rsp()**
Template: Response Forest Plot

**template_forest_tte()**
Template: Survival Forest Plot

**template_g_ci()**
Template: Confidence Interval Plot

**template_g_ipp()**
Template: Individual Patient Plots

**template_g_km()**
Template: Kaplan-Meier

**template_g_lineplot()**
Template: Line Plot

**template_laboratory()**
Template: Laboratory

**template_logistic()**
Template: Logistic Regression

**template_medical_history()**
Template: Medical History

**template_mult_events()**
Template: Events by Term

**template_patient_timeline()**
Template: Patient Timeline Tab

**template_prior_medication()**
Template: Prior Medication

**template_shift_by_arm_by_worst()**
Template: Shift by Arm

**template_shift_by_arm()**
Template: Shift by Arm

**template_shift_by_grade()**
Template: Grade Summary Table

**template_smq()**
Adverse Events Table by Standardized 
list("MedDRA")
 Query

**template_summary_by()**
Template: Summarize Variables by Row Groups Module

**template_summary()**
Template: Summary of Variables

**template_therapy()**
Template: Therapy

**template_tte()**
Template: Time-to-Event

**template_vitals()**
Template: Vitals

**validate_arm()**
Check if vector is valid as to be used as a treatment arm variable

**validate_standard_inputs()**
Validate standard input values for a teal module

### tern 


**abnormal_by_baseline()**
Patient Counts with Abnormal Range Values by Baseline Status

**abnormal_by_marked()**
Count patients with marked laboratory abnormalities

**abnormal_by_worst_grade_worsen()**
Patient Counts for Laboratory Events (Worsen From Baseline) by Highest Grade Post-Baseline

**abnormal_by_worst_grade()**
Patient Counts with the Most Extreme Post-baseline Toxicity Grade per Direction of Abnormality

**abnormal()**
Patient Counts with Abnormal Range Values

**afun_selected_stats()**
Get Selected Statistics Names

**argument_convention()**
Standard Arguments

**arrange_grobs()**
Arrange Multiple Grobs

**as_factor_keep_attributes()**
Conversion of a Vector to a Factor

**assertions()**
Additional Assertions for 
list("checkmate")

**bins_percent_labels()**
Labels for Bins in Percent

**c_label_n()**
Content Row Function to Add Row Total to Labels

**cfun_by_flag()**
Constructor for Content Functions given Data Frame with Flag Input

**check_diff_prop_ci()**
Check: Proportion Difference Arguments

**check_same_n()**
Check Element Dimension

**combine_counts()**
Combine Counts

**combine_vectors()**
Combine Two Vectors Element Wise

**count_cumulative()**
Cumulative Counts with Thresholds

**count_missed_doses()**
Counting Missed Doses

**count_patients_events_in_cols()**
Counting Patients and Events in Columns

**decorate_grob_factory()**
Update Page Number

**empty_vector_if_na()**
Return an empty numeric if all elements are 
list("NA")
.

**estimate_coef()**
Hazard Ratio Estimation in Interactions

**extract_by_name()**
Extract Elements by Name

**forest_viewport()**
Create a Viewport Tree for the Forest Plot

**format_xx()**
Formatting: XX as Formatting Function

**get_covariates()**
Utility function to return a named list of covariate names.

**groups_list_to_df()**
Convert List of Groups to Data Frame

**incidence_rate()**
Incidence rate

**labels_or_names()**
Labels or Names of List Elements

**make_names()**
Make Names Without Dots

**muffled_car_anova()**
Muffled 
list("car::Anova")

**n_available()**
Number of Available (Non-Missing Entries) in a Vector

**prop_diff_test()**
Difference Test for Two Proportions

**prune_occurrences()**
Occurrence Table Pruning

**range_noinf()**
Re-implemented 
list(list("range.default"))
 default S3 method for numerical objects only.

It returns 
list("c(NA, NA)")
 instead of 
list("c(-Inf, Inf)")
 for zero-length data

without any warnings.

**replace_emptys_with_na()**
Replace all empty string values in data frame

**response_subgroups()**
Tabulate Binary Response by Subgroup

**rtables_access()**
list("rtables")
 Access Helper Functions

**s_cox_multivariate()**
Multivariate Cox Model - summarized results

**split_text_grob()**
Split Text According To Available Text Width

**study_arm()**
Indicate Study Arm Variable in Formula

**summarize_ancova()**
Summary for analysis of covariance (ANCOVA).

**summarize_change()**
Summarize the Change from Baseline or Absolute Baseline Values

**summarize_patients_exposure_in_cols()**
Counting Patients Summing Exposure Across All Patients in Columns

**summary_formats()**
Format Function for Descriptive Statistics

**summary_labels()**
Label Function for Descriptive Statistics

**survival_coxph_pairwise()**
Pairwise CoxPH model

**survival_duration_subgroups()**
Tabulate Survival Duration by Subgroup

**survival_time()**
Survival Time Analysis

**survival_timepoint()**
Survival Time Point Analysis

**try_car_anova()**
list("tryCatch")
 around 
list("car::Anova")

**unlist_and_blank_na()**
Blank for Missing Input
