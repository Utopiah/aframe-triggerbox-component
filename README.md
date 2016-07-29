Trigger box for AframeVR, emit an event on the moving entity once it enters and leaves a predefined area

Usage camera triggerbox="triggereventname: mytriggerbox" will make a 1x1x1 box will emits event mytriggerbox_entered once the camera moves in and event mytriggerbox_entered once the camera leaves it. It can also be used on other entity e.g. an enemy or a bonus.

Demo http://output.jsbin.com/gogoci

inspired by https://github.com/atomicguy/aframe-fence-component/

Todo :
1. check that https://aframe.io/docs/master/core/component.html#multiple-instancing does work as expected
