##############################################################################
# CMake
##############################################################################

cmake_minimum_required(VERSION 2.8.3)
project(rocon_interaction_msgs)

##############################################################################
# Dependencies
##############################################################################

find_package(catkin REQUIRED COMPONENTS 
    message_generation 
    rocon_std_msgs
)

##############################################################################
# Messages
##############################################################################

add_message_files(
  DIRECTORY msg
  FILES
  #Constants.msg
  ErrorCodes.msg
  Interaction.msg
  InteractiveClient.msg
  InteractiveClients.msg
  RemoconStatus.msg
  Roles.msg
  Strings.msg
)

add_service_files(
  DIRECTORY srv
  FILES
  GetInteraction.srv
  GetInteractions.srv
  RequestInteraction.srv
  SetInteractions.srv
)

generate_messages(DEPENDENCIES rocon_std_msgs)

##############################################################################
# Package
##############################################################################

catkin_package(CATKIN_DEPENDS
  message_runtime
  rocon_std_msgs
)
