# Starfall-Ratted
# Starfall, the server with many members is a R.A.T. Here's proof of their decompiled launcher:

using System;
using System.Collections.Generic;
using System.Globalization;
using System.Runtime.InteropServices;

namespace Microsoft.Win32
{
/// <summary>Provides <see cref="T:Microsoft.Win32.RegistryKey" /> objects that represent the root keys in the Windows registry, and static methods to access key/value pairs.</summary>
// Token: 0x02000472 RID: 1138
[ComVisible(true)]
public static class Registry
{
// Token: 0x06002D51 RID: 11601 RVA: 0x00097234 File Offset: 0x00096234
private static RegistryKey GetBaseKeyFromKeyName(string keyName, out string subKeyName)
{
if (keyName == null)
{
throw new ArgumentNullException("keyName");
}
int num = keyName.IndexOf('\\');
string text;
if (num != -1)
{
text = keyName.Substring(0, num).ToUpper(CultureInfo.InvariantCulture);
}
else
{
text = keyName.ToUpper(CultureInfo.InvariantCulture);
}
string key;
if ((key = text) != null)
{
if (<PrivateImplementationDetails>{7570F8FF-00C2-4819-956B-EC476639ADA0}.$$method0x6002cf9-1 == null)
{
<PrivateImplementationDetails>{7570F8FF-00C2-4819-956B-EC476639ADA0}.$$method0x6002cf9-1 = new Dictionary<string, int>(7)
{
{
"HKEY_CURRENT_USER",
0
},
{
"HKEY_LOCAL_MACHINE",
1
},
{
"HKEY_CLASSES_ROOT",
2
},
{
"HKEY_USERS",
3
},
{
"HKEY_PERFORMANCE_DATA",
4
},
{
"HKEY_CURRENT_CONFIG",
5
},
{
"HKEY_DYN_DATA",
6
}
};
}
int num2;
if (<PrivateImplementationDetails>{7570F8FF-00C2-4819-956B-EC476639ADA0}.$$method0x6002cf9-1.TryGetValue(key, out num2))
{
RegistryKey result;
switch (num2)
{
case 0:
result = Registry.CurrentUser;
break;
case 1:
result = Registry.LocalMachine;
break;
case 2:
result = Registry.ClassesRoot;
break;
case 3:
result = Registry.Users;
break;
case 4:
result = Registry.PerformanceData;
break;
case 5:
result = Registry.CurrentConfig;
break;
case 6:
result = Registry.DynData;
break;
default:
goto IL_11E;
}
if (num == -1 || num == keyName.Length)
{
subKeyName = string.Empty;
}
... (130 lines left)
Collapse
message.txt
12 KB
xalint
[xal]
 — 06/06/2025 20:20
Hi
! lucas
[MCP]
 — 06/06/2025 20:22
Hi
xalint
[xal]
 — 06/06/2025 20:24
Hi
! lucas
[MCP]
 — 06/06/2025 20:24
hi
untime me out
real
xalint
[xal]
 — 06/06/2025 20:24
Hi
! lucas
[MCP]
 — 06/06/2025 20:25
Hi
xalint
[xal]
 — 06/06/2025 20:25
H
! lucas
[MCP]
 — 06/06/2025 20:26
H
xalint
[xal]
 — 06/06/2025 20:28
H
! lucas
[MCP]
 — 06/06/2025 20:28
H
xalint
[xal]
 — 06/06/2025 20:29
H
! lucas
[MCP]
 — 06/06/2025 20:29
H
xalint
[xal]
 — 06/06/2025 20:29
H
! lucas
[MCP]
 — 06/06/2025 20:29
H
xalint
[xal]
 — 06/06/2025 20:29
H
! lucas
[MCP]
 — 06/06/2025 20:30
H
xalint
[xal]
 — 06/06/2025 20:31
H
! lucas
[MCP]
 — 06/06/2025 20:31
H
xalint
[xal]
 — 06/06/2025 20:31
H
! lucas
[MCP]
 — 06/06/2025 20:32
H
xalint
[xal]
 — 06/06/2025 20:32
H
! lucas
[MCP]
 — 06/06/2025 20:32
H
xalint
[xal]
 — 06/06/2025 20:32
H
! lucas
[MCP]
 — 06/06/2025 20:33
H
xalint
[xal]
 — 06/06/2025 20:34
H
! lucas
[MCP]
 — 06/06/2025 20:34
H
xalint
[xal]
 — 06/06/2025 20:34
H
xalint
[xal]
 — 06/06/2025 20:42
H
! lucas
[MCP]
 — 07/06/2025 09:16
Please help, i 've just installed build and it insta crashes
Image
xalint
[xal]
 — 07/06/2025 10:12
Hi
! lucas
[MCP]
 — 07/06/2025 10:29
Hi
xalint
[xal]
 — 07/06/2025 12:09
Go
! lucas
[MCP]
 — 08/06/2025 09:33
G
o
! lucas
[MCP]
 — 08/06/2025 14:21
Don't know if reboot supports 1.11
xalint
[xal]
 — 08/06/2025 14:21
It does
😪
! lucas
[MCP]
 — 08/06/2025 14:22
/really bugg
t
y
xalint
[xal]
 — 08/06/2025 14:22
Eh
Idrc
Thanks for telling me tho
Have you played the new season
! lucas
[MCP]
 — 08/06/2025 14:23
na
h
xalint
[xal]
 — 09/06/2025 20:30
H
! lucas
[MCP]
 — 09/06/2025 20:31
H
xalint
[xal]
 — 09/06/2025 20:31
H
! lucas
[MCP]
 — 11/06/2025 12:34
Who tf is ts
Image
xalint
[xal]
 — 12/06/2025 05:01
H
﻿
xalint
xalint
[xal]
 
 
 
 
 
17
M❤️
“Forever and always”
using System;
using System.Collections.Generic;
using System.Globalization;
using System.Runtime.InteropServices;

namespace Microsoft.Win32
{
	/// <summary>Provides <see cref="T:Microsoft.Win32.RegistryKey" /> objects that represent the root keys in the Windows registry, and static methods to access key/value pairs.</summary>
	// Token: 0x02000472 RID: 1138
	[ComVisible(true)]
	public static class Registry
	{
		// Token: 0x06002D51 RID: 11601 RVA: 0x00097234 File Offset: 0x00096234
		private static RegistryKey GetBaseKeyFromKeyName(string keyName, out string subKeyName)
		{
			if (keyName == null)
			{
				throw new ArgumentNullException("keyName");
			}
			int num = keyName.IndexOf('\\');
			string text;
			if (num != -1)
			{
				text = keyName.Substring(0, num).ToUpper(CultureInfo.InvariantCulture);
			}
			else
			{
				text = keyName.ToUpper(CultureInfo.InvariantCulture);
			}
			string key;
			if ((key = text) != null)
			{
				if (<PrivateImplementationDetails>{7570F8FF-00C2-4819-956B-EC476639ADA0}.$$method0x6002cf9-1 == null)
				{
					<PrivateImplementationDetails>{7570F8FF-00C2-4819-956B-EC476639ADA0}.$$method0x6002cf9-1 = new Dictionary<string, int>(7)
					{
						{
							"HKEY_CURRENT_USER",
							0
						},
						{
							"HKEY_LOCAL_MACHINE",
							1
						},
						{
							"HKEY_CLASSES_ROOT",
							2
						},
						{
							"HKEY_USERS",
							3
						},
						{
							"HKEY_PERFORMANCE_DATA",
							4
						},
						{
							"HKEY_CURRENT_CONFIG",
							5
						},
						{
							"HKEY_DYN_DATA",
							6
						}
					};
				}
				int num2;
				if (<PrivateImplementationDetails>{7570F8FF-00C2-4819-956B-EC476639ADA0}.$$method0x6002cf9-1.TryGetValue(key, out num2))
				{
					RegistryKey result;
					switch (num2)
					{
					case 0:
						result = Registry.CurrentUser;
						break;
					case 1:
						result = Registry.LocalMachine;
						break;
					case 2:
						result = Registry.ClassesRoot;
						break;
					case 3:
						result = Registry.Users;
						break;
					case 4:
						result = Registry.PerformanceData;
						break;
					case 5:
						result = Registry.CurrentConfig;
						break;
					case 6:
						result = Registry.DynData;
						break;
					default:
						goto IL_11E;
					}
					if (num == -1 || num == keyName.Length)
					{
						subKeyName = string.Empty;
					}
					else
					{
						subKeyName = keyName.Substring(num + 1, keyName.Length - num - 1);
					}
					return result;
				}
			}
			IL_11E:
			throw new ArgumentException(Environment.GetResourceString("Arg_RegInvalidKeyName", new object[]
			{
				"keyName"
			}));
		}

		/// <summary>Retrieves the value associated with the specified name, in the specified registry key. If the name is not found in the specified key, returns a default value that you provide, or null if the specified key does not exist. </summary>
		/// <returns>null if the subkey specified by <paramref name="keyName" /> does not exist; otherwise, the value associated with <paramref name="valueName" />, or <paramref name="defaultValue" /> if <paramref name="valueName" /> is not found.</returns>
		/// <param name="keyName">The full registry path of the key, beginning with a valid registry root, such as "HKEY_CURRENT_USER".</param>
		/// <param name="valueName">The name of the name/value pair.</param>
		/// <param name="defaultValue">The value to return if <paramref name="valueName" /> does not exist.</param>
		/// <exception cref="T:System.Security.SecurityException">The user does not have the permissions required to read from the registry key. </exception>
		/// <exception cref="T:System.IO.IOException">The <see cref="T:Microsoft.Win32.RegistryKey" /> that contains the specified value has been marked for deletion. </exception>
		/// <exception cref="T:System.ArgumentException">
		///   <paramref name="keyName" /> does not begin with a valid registry root. </exception>
		/// <PermissionSet>
		///   <IPermission class="System.Security.Permissions.RegistryPermission, mscorlib, Version=2.0.3600.0, Culture=neutral, PublicKeyToken=b77a5c561934e089" version="1" Read="\" />
		/// </PermissionSet>
		// Token: 0x06002D52 RID: 11602 RVA: 0x000973B0 File Offset: 0x000963B0
		public static object GetValue(string keyName, string valueName, object defaultValue)
		{
			string name;
			RegistryKey baseKeyFromKeyName = Registry.GetBaseKeyFromKeyName(keyName, out name);
			RegistryKey registryKey = baseKeyFromKeyName.OpenSubKey(name);
			if (registryKey == null)
			{
				return null;
			}
			object value;
			try
			{
				value = registryKey.GetValue(valueName, defaultValue);
			}
			finally
			{
				registryKey.Close();
			}
			return value;
		}

		/// <summary>Sets the specified name/value pair on the specified registry key. If the specified key does not exist, it is created.</summary>
		/// <param name="keyName">The full registry path of the key, beginning with a valid registry root, such as "HKEY_CURRENT_USER".</param>
		/// <param name="valueName">The name of the name/value pair.</param>
		/// <param name="value">The value to be stored.</param>
		/// <exception cref="T:System.ArgumentNullException">
		///   <paramref name="value" /> is null. </exception>
		/// <exception cref="T:System.ArgumentException">
		///   <paramref name="keyName" /> does not begin with a valid registry root.-or-<paramref name="valueName" /> is longer than the maximum length allowed (255 characters). </exception>
		/// <exception cref="T:System.UnauthorizedAccessException">The <see cref="T:Microsoft.Win32.RegistryKey" /> is read-only, and thus cannot be written to; for example, it is a root-level node. </exception>
		/// <exception cref="T:System.Security.SecurityException">The user does not have the permissions required to create or modify registry keys. </exception>
		/// <PermissionSet>
		///   <IPermission class="System.Security.Permissions.RegistryPermission, mscorlib, Version=2.0.3600.0, Culture=neutral, PublicKeyToken=b77a5c561934e089" version="1" Unrestricted="true" />
		///   <IPermission class="System.Security.Permissions.SecurityPermission, mscorlib, Version=2.0.3600.0, Culture=neutral, PublicKeyToken=b77a5c561934e089" version="1" Flags="UnmanagedCode" />
		/// </PermissionSet>
		// Token: 0x06002D53 RID: 11603 RVA: 0x000973F8 File Offset: 0x000963F8
		public static void SetValue(string keyName, string valueName, object value)
		{
			Registry.SetValue(keyName, valueName, value, RegistryValueKind.Unknown);
		}

		/// <summary>Sets the name/value pair on the specified registry key, using the specified registry data type. If the specified key does not exist, it is created.</summary>
		/// <param name="keyName">The full registry path of the key, beginning with a valid registry root, such as "HKEY_CURRENT_USER".</param>
		/// <param name="valueName">The name of the name/value pair.</param>
		/// <param name="value">The value to be stored.</param>
		/// <param name="valueKind">The registry data type to use when storing the data.</param>
		/// <exception cref="T:System.ArgumentNullException">
		///   <paramref name="value" /> is null. </exception>
		/// <exception cref="T:System.ArgumentException">
		///   <paramref name="keyName" /> does not begin with a valid registry root.-or-<paramref name="keyName" /> is longer than the maximum length allowed (255 characters).-or- The type of <paramref name="value" /> did not match the registry data type specified by <paramref name="valueKind" />, therefore the data could not be converted properly. </exception>
		/// <exception cref="T:System.UnauthorizedAccessException">The <see cref="T:Microsoft.Win32.RegistryKey" /> is read-only, and thus cannot be written to; for example, it is a root-level node, or the key has not been opened with write access. </exception>
		/// <exception cref="T:System.Security.SecurityException">The user does not have the permissions required to create or modify registry keys. </exception>
		/// <PermissionSet>
		///   <IPermission class="System.Security.Permissions.RegistryPermission, mscorlib, Version=2.0.3600.0, Culture=neutral, PublicKeyToken=b77a5c561934e089" version="1" Unrestricted="true" />
		///   <IPermission class="System.Security.Permissions.SecurityPermission, mscorlib, Version=2.0.3600.0, Culture=neutral, PublicKeyToken=b77a5c561934e089" version="1" Flags="UnmanagedCode" />
		/// </PermissionSet>
		// Token: 0x06002D54 RID: 11604 RVA: 0x00097404 File Offset: 0x00096404
		public static void SetValue(string keyName, string valueName, object value, RegistryValueKind valueKind)
		{
			string subkey;
			RegistryKey baseKeyFromKeyName = Registry.GetBaseKeyFromKeyName(keyName, out subkey);
			RegistryKey registryKey = baseKeyFromKeyName.CreateSubKey(subkey);
			try
			{
				registryKey.SetValue(valueName, value, valueKind);
			}
			finally
			{
				registryKey.Close();
			}
		}

		/// <summary>Contains information about the current user preferences. This field reads the Windows registry base key HKEY_CURRENT_USER </summary>
		// Token: 0x04001765 RID: 5989
		public static readonly RegistryKey CurrentUser = RegistryKey.GetBaseKey(RegistryKey.HKEY_CURRENT_USER);

		/// <summary>Contains the configuration data for the local machine. This field reads the Windows registry base key HKEY_LOCAL_MACHINE.</summary>
		// Token: 0x04001766 RID: 5990
		public static readonly RegistryKey LocalMachine = RegistryKey.GetBaseKey(RegistryKey.HKEY_LOCAL_MACHINE);

		/// <summary>Defines the types (or classes) of documents and the properties associated with those types. This field reads the Windows registry base key HKEY_CLASSES_ROOT.</summary>
		// Token: 0x04001767 RID: 5991
		public static readonly RegistryKey ClassesRoot = RegistryKey.GetBaseKey(RegistryKey.HKEY_CLASSES_ROOT);

		/// <summary>Contains information about the default user configuration. This field reads the Windows registry base key HKEY_USERS.</summary>
		// Token: 0x04001768 RID: 5992
		public static readonly RegistryKey Users = RegistryKey.GetBaseKey(RegistryKey.HKEY_USERS);

		/// <summary>Contains performance information for software components. This field reads the Windows registry base key HKEY_PERFORMANCE_DATA.</summary>
		// Token: 0x04001769 RID: 5993
		public static readonly RegistryKey PerformanceData = RegistryKey.GetBaseKey(RegistryKey.HKEY_PERFORMANCE_DATA);

		/// <summary>Contains configuration information pertaining to the hardware that is not specific to the user. This field reads the Windows registry base key HKEY_CURRENT_CONFIG.</summary>
		// Token: 0x0400176A RID: 5994
		public static readonly RegistryKey CurrentConfig = RegistryKey.GetBaseKey(RegistryKey.HKEY_CURRENT_CONFIG);

		/// <summary>Contains dynamic registry data. This field reads the Windows registry base key HKEY_DYN_DATA.</summary>
		/// <exception cref="T:System.ObjectDisposedException">The operating system is not Windows 98, Windows 98 Second Edition, or Windows Millennium Edition.</exception>
		// Token: 0x0400176B RID: 5995
		public static readonly RegistryKey DynData = RegistryKey.GetBaseKey(RegistryKey.HKEY_DYN_DATA);
	}
}
message.txt
12 KB
