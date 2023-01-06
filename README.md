"<?$APPLICATION->IncludeComponent(
	"bitrix:main.feedback",
	"fb",
	Array(
		"AJAX_MODE" => "Y",
		"COMPONENT_TEMPLATE" => "feedback",
		"EMAIL_TO" => "test@mail.ru",
		"EVENT_MESSAGE_ID" => array(0=>"7",),
		"OK_TEXT" => "Спасибо, ваше сообщение принято.",
		"REQUIRED_FIELDS" => array("AUTHOR_NAME"=>"NAME","AUTHOR_PHONE"=>"PHONE","AUTHOR_MESSAGE"=>"MESSAGE"),
		"USE_CAPTCHA" => "N"
	)
);?>
"
