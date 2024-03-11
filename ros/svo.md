# SVO

- OAK-D camera does not publish exactly synced stereo messages. SVO expected uses by default ExactTime sync policy, change it to ApproximateTime to allow stereo mode to work.
- https://github.com/uzh-rpg/rpg_svo_pro_open/blob/ca371f304637e7fb355cf4624d0a02da4e3da220/svo_ros/src/svo_interface.cpp#L504
