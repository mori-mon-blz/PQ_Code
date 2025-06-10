let
  //cwb = Excel.CurrentWorkbook(),
  fn_get_cell_value = ( wb as table, rng_name as text ) as text =>
    let 
      content = wb{[Name = rng_name]}[Content]
    in 
      content[Column1]{0}
in
  fn_get_cell_value
