# signature
Protocol signature class

Use next code after include this class in php file
$arrReq['pg_sig'] = PG_Signature::make('script_name.php', $arrReq, $MERCHANT_SECRET_KEY);

//where $arrReq is array with request params ,  $MERCHANT_SECRET_KEY is string 
