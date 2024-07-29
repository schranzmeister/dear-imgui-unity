Link für URP (UNSAFE Error)
https://github.com/realgamessoftware/dear-imgui-unity.git#101996d5fced0e6601279e89cb753c474343e8aa
    
    
    For other people running into this issue, a good solution is to specifically import DearIMGui as a git repo in the package manager with this commit hash specified. I will write out the steps below, that I took to get Matt's cool changes!
    Steps

    Follow the README instructions to import the package in the package manager as a .git repo, but instead put this commit's hash after like this: https://github.com/realgamessoftware/dear-imgui-unity.git#101996d5fced0e6601279e89cb753c474343e8aa

    Import, and now all the compiler errors should have gone away

    Next, depending on URP or not, follow the other useful issue chat in this repo that clarify that setup (#6)
    Reference

    https://docs.unity3d.com/Manual/upm-git.html#revision
    NB

    I was attempting to get this to work with OVR, doesn't seem to show up at all. Just a note to the next person!

That works perfectly, but I have an issue with the In-Engine Gizmos not rendering when Imgui is rendering, any fixes for that you can share?
