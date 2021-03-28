Require opencart/system/startup.php manual modification:

function start($application_config) {
    require_once(DIR_SYSTEM . 'framework.php');
}

Should be:

function start($application_config) {
    require_once(modification(DIR_SYSTEM . 'framework.php'));
}