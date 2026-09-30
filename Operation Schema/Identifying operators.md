| op_id | operation | purpose |
| :--- | :--- | :--- |
| OP01 | perform_self_check | Tests the functionality of all essential sensors and environmental-control devices during startup before entering monitoring mode. |
| OP02 | record_artifact_info | Stores the unique identification details and required environmental limits of an artifact when placed inside the chamber. |
| OP03 | monitor_environment | Continuously tracks real-time sensor streams for temperature, humidity, light exposure, vibration, door status, and power availability. |
| OP04 | verify_door_status | Checks whether the chamber door is open or closed to determine eligibility for active conservation. |
| OP05 | activate_conservation | Initiates the normal environmental conservation process once preconditions like door closure and profile loading are met. |
| OP06 | adjust_temperature | Commands the environmental-control mechanism to alter and restore chamber temperature when it drifts outside permitted limits. |
| OP07 | adjust_humidity | Commands moisture-control mechanisms to correct humidity levels when they drift outside acceptable boundaries. |
| OP08 | verify_environmental_recovery | Evaluates post-correction sensor feedback to confirm that temperature or humidity has actually returned to the safe range. |
| OP09 | trigger_protection_mode | Activates emergency safeguards (reduces lighting, boosts controls, and alerts operators) if environmental recovery fails within the allowed period. |
| OP10 | respond_to_vibration | Temporarily suspends operations that increase risk to the artifact when a significant vibration event is detected. |
| OP11 | verify_stabilization | Confirms that vibration levels have remained below the permitted threshold for the required continuous stabilization period before resuming operations. |
| OP12 | handle_power_loss | Switches to an emergency backup power source or logs the incident and initiates a safe system shutdown if power fails. |
| OP13 | authorize_artifact_removal | Validates that the chamber is in a safe condition and no active protection responses are underway before allowing an operator to remove the artifact. |
