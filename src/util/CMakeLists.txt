target_sources(${DAISY_CORE_NAME} PRIVATE
  anystate.C
  assertion.C
  complex_functions.C
  depth.C
  filepos.C
  format.C
  format_LaTeX.C
  gaussj.C
  hyp_2F1.C
  iterative.C
  lexer.C
  lexer_data.C
  lexer_flux.C
  lexer_soil.C
  lexer_table.C
  mathlib.C
  nrutil.C
  path.C
  point.C
  run_cmd.C
  scope.C
  scope_exchange.C
  scope_id.C
  scope_model.C
  scope_multi.C
  scope_soil.C
  scope_sources.C
  scope_table.C
  scope_xysources.C
  scopesel.C
  solver.C
  solver_cxsparse.C
  solver_none.C
  solver_ublas.C
)
