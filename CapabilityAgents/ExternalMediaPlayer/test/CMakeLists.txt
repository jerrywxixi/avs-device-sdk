cmake_minimum_required(VERSION 3.1 FATAL_ERROR)

set(INCLUDE_PATH
	"${ExternalMediaPlayer_INCLUDE_DIRS}"
	"${AVSCommon_SOURCE_DIR}/Utils/test"
    "${CertifiedSender_SOURCE_DIR}/test")

discover_unit_tests("${INCLUDE_PATH}" "ExternalMediaPlayer;UtilsCommonTestLib;SDKInterfacesTests;CertifiedSenderCommonTestLib")
