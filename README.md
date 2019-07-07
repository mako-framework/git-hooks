# Git Hooks

## pre-commit

The ```pre-commit``` hook runs modified files through ```php-cs-fixer``` with the following fixers:

* array_syntax (['syntax' => 'short'])
* blank_line_after_namespace
* blank_line_after_opening_tag
* cast_spaces
* combine_nested_dirname
* concat_space (['spacing' => 'one'])
* elseif
* encoding
* full_opening_tag
* function_declaration (['closure_function_spacing' => 'none'])
* function_to_constant
* function_typehint_space
* linebreak_after_opening_tag
* list_syntax (['syntax' => 'short'])
* logical_operators
* lowercase_cast
* lowercase_constants
* lowercase_keywords
* lowercase_static_reference
* magic_constant_casing
* magic_method_casing
* method_argument_space
* native_function_casing
* no_alias_functions
* no_blank_lines_after_phpdoc
* no_closing_tag
* no_empty_statement
* no_extra_blank_lines
* no_leading_import_slash
* no_leading_namespace_whitespace
* no_singleline_whitespace_before_semicolons
* no_spaces_inside_parenthesis
* no_trailing_comma_in_list_call
* no_trailing_comma_in_singleline_array
* no_trailing_whitespace
* no_trailing_whitespace_in_comment
* no_unused_imports
* no_whitespace_before_comma_in_array
* no_whitespace_in_blank_line
* non_printable_character
* normalize_index_brace
* object_operator_without_whitespace
* ordered_imports (['imports_order' => ['class', 'function', 'const']])
* phpdoc_align
* phpdoc_indent
* phpdoc_no_access
* phpdoc_order
* phpdoc_scalar
* phpdoc_summary
* phpdoc_to_comment
* phpdoc_trim
* phpdoc_types
* pow_to_exponentiation
* return_type_declaration
* short_scalar_cast
* simple_to_complex_string_variable
* single_blank_line_at_eof
* single_blank_line_before_namespace
* single_import_per_statement
* single_line_after_imports
* single_line_comment_style (['comment_types' => ['hash']])
* single_quote
* space_after_semicolon
* standardize_not_equals
* switch_case_semicolon_to_colon
* switch_case_space
* trailing_comma_in_multiline_array
* trim_array_spaces
* visibility_required
* void_return
* whitespace_after_comma_in_array
