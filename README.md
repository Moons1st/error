Exception filling window for Verse.ImmediateWindow: System.TypeLoadException: Could not resolve type with token 0100001b (from typeref, class/assembly Harmony.HarmonyInstance, 0Harmony, Version=1.2.0.1, Culture=neutral, PublicKeyToken=null)
  at (wrapper managed-to-native) System.Reflection.MonoMethodInfo.get_method_info(intptr,System.Reflection.MonoMethodInfo&)
  at System.Reflection.MonoMethodInfo.GetMethodInfo (System.IntPtr handle) [0x00000] in <567df3e0919241ba98db88bec4c6696f>:0 
  at System.Reflection.MonoMethod.GetPseudoCustomAttributes () [0x00002] in <567df3e0919241ba98db88bec4c6696f>:0 
  at System.MonoCustomAttrs.GetPseudoCustomAttributes (System.Reflection.ICustomAttributeProvider obj, System.Type attributeType) [0x0000a] in <567df3e0919241ba98db88bec4c6696f>:0 
  at System.MonoCustomAttrs.GetCustomAttributesBase (System.Reflection.ICustomAttributeProvider obj, System.Type attributeType, System.Boolean inheritedOnly) [0x0001f] in <567df3e0919241ba98db88bec4c6696f>:0 
  at System.MonoCustomAttrs.GetCustomAttributes (System.Reflection.ICustomAttributeProvider obj, System.Type attributeType, System.Boolean inherit) [0x00037] in <567df3e0919241ba98db88bec4c6696f>:0 
  at System.Reflection.MonoMethod.GetCustomAttributes (System.Type attributeType, System.Boolean inherit) [0x00000] in <567df3e0919241ba98db88bec4c6696f>:0 
  at Verse.GenAttribute.TryGetAttribute[T] (System.Reflection.MemberInfo memberInfo, T& customAttribute) [0x00000] in <0ee2c524c4be441e9b7f8bfcb20aca6f>:0 
  at Verse.Dialog_DebugActionsMenu..ctor () [0x0003e] in <0ee2c524c4be441e9b7f8bfcb20aca6f>:0 
  at Verse.DebugWindowsOpener.ToggleDebugActionsMenu () [0x0001c] in <0ee2c524c4be441e9b7f8bfcb20aca6f>:0 
  at (wrapper dynamic-method) Verse.DebugWindowsOpener.DMD<DMD<DrawButtons_Patch0>?-2046033920::DrawButtons_Patch0>(Verse.DebugWindowsOpener)
  at Verse.ImmediateWindow.DoWindowContents (UnityEngine.Rect inRect) [0x00000] in <0ee2c524c4be441e9b7f8bfcb20aca6f>:0 
  at Verse.Window.InnerWindowOnGUI (System.Int32 x) [0x00165] in <0ee2c524c4be441e9b7f8bfcb20aca6f>:0 
 
