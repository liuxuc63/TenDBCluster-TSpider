ADD_DEFINITIONS(-DHAVE_RESPONSE_TIME_DISTRIBUTION)
MYSQL_ADD_PLUGIN(QUERY_RESPONSE_TIME query_response_time.cc plugin.cc MANDATORY)
