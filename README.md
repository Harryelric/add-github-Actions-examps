[DifXFrontend.log](https://github.com/Harryelric/add-github-Actions-examps/files/6961106/DifXFrontend.log)
[IntelME.log](https://github.com/Harryelric/add-github-Actions-examps/files/6961107/IntelME.log)
[IntelME_MSI.log](https://github.com/Harryelric/add-github-Actions-examps/files/6961108/IntelME_MSI.log)
# add-github-Actions-examps
add github Actions examps
name: GitHub Actions Demo
on: [push]
jobs:
  Explore-GitHub-Actions:
    runs-on: ubuntu-latest
    steps:
      - run: echo "🎉 The job was automatically triggered by a ${{ github.event_name }} event."
      - run: echo "🐧 This job is now running on a ${{ runner.os }} server hosted by GitHub!"
      - run: echo "🔎 The name of your branch is ${{ github.ref }} and your repository is ${{ github.repository }}."
      - name: Check out repository code
        uses: actions/checkout@v2
      - run: echo "💡 The ${{ github.repository }} repository has been cloned to the runner."
      - run: echo "🖥️ The workflow is now ready to test your code on the runner."
      - name: List files in the repository
        run: |
          ls ${{ github.workspace }}
      - run: echo "🍏 This job's status is ${{ job.status }}."MSI (s) (08:18) [22:48:49:312]: Note: 1: 2205 2:  3: ActionText 
Action ended 22:48:49: RegisterProduct. Return value 1.
Action start 22:48:49: PublishFeatures.
MSI (s) (08:18) [22:48:49:312]: Doing action: PublishProduct
MSI (s) (08:18) [22:48:49:312]: Note: 1: 2205 2:  3: ActionText 
Action ended 22:48:49: PublishFeatures. Return value 1.
MSI (s) (08:18) [22:48:49:312]: Note: 1: 2205 2:  3: Icon 
MSI (s) (08:18) [22:48:49:312]: Note: 1: 2228 2:  3: Icon 4: SELECT `Name`, `Data` FROM `Icon` 
Action start 22:48:49: PublishProduct.
MSI (s) (08:18) [22:48:49:312]: Doing action: setPermitsToLogFolder.8994F7B6_3CCC_48D6_890A_09EEEA149781
MSI (s) (08:18) [22:48:49:312]: Note: 1: 2205 2:  3: ActionText 
Action ended 22:48:49: PublishProduct. Return value 1.
Action start 22:48:49: setPermitsToLogFolder.8994F7B6_3CCC_48D6_890A_09EEEA149781.
MSI (s) (08:18) [22:48:49:312]: Doing action: setPermitsToLogFolder.9B48670B_D6C7_46FD_9AE5_24CBB7D30A26
MSI (s) (08:18) [22:48:49:312]: Note: 1: 2205 2:  3: ActionText 
Action ended 22:48:49: setPermitsToLogFolder.8994F7B6_3CCC_48D6_890A_09EEEA149781. Return value 1.
Action start 22:48:49: setPermitsToLogFolder.9B48670B_D6C7_46FD_9AE5_24CBB7D30A26.
MSI (s) (08:18) [22:48:49:312]: Doing action: DeleteTask.199BDD9A_24A6_4823_97EE_2CE1ACDA55D5
MSI (s) (08:18) [22:48:49:312]: Note: 1: 2205 2:  3: ActionText 
Action ended 22:48:49: setPermitsToLogFolder.9B48670B_D6C7_46FD_9AE5_24CBB7D30A26. Return value 1.
Action start 22:48:49: DeleteTask.199BDD9A_24A6_4823_97EE_2CE1ACDA55D5.
MSI (s) (08:18) [22:48:49:312]: Doing action: ImportTask.199BDD9A_24A6_4823_97EE_2CE1ACDA55D5
MSI (s) (08:18) [22:48:49:312]: Note: 1: 2205 2:  3: ActionText 
Action ended 22:48:49: DeleteTask.199BDD9A_24A6_4823_97EE_2CE1ACDA55D5. Return value 1.
Action start 22:48:49: ImportTask.199BDD9A_24A6_4823_97EE_2CE1ACDA55D5.
MSI (s) (08:18) [22:48:49:312]: Doing action: AlterTask.199BDD9A_24A6_4823_97EE_2CE1ACDA55D5
MSI (s) (08:18) [22:48:49:312]: Note: 1: 2205 2:  3: ActionText 
Action ended 22:48:49: ImportTask.199BDD9A_24A6_4823_97EE_2CE1ACDA55D5. Return value 1.
Action start 22:48:49: AlterTask.199BDD9A_24A6_4823_97EE_2CE1ACDA55D5.
MSI (s) (08:18) [22:48:49:312]: Doing action: setPermitsToLogFolder.E6E6A000_274B_4499_9314_1587794DB59B
MSI (s) (08:18) [22:48:49:312]: Note: 1: 2205 2:  3: ActionText 
Action ended 22:48:49: AlterTask.199BDD9A_24A6_4823_97EE_2CE1ACDA55D5. Return value 1.
Action start 22:48:49: setPermitsToLogFolder.E6E6A000_274B_4499_9314_1587794DB59B.
MSI (s) (08:18) [22:48:49:327]: Doing action: setPermitsToLogFolder.B7CF4EA4_7FB9_41F3_BE44_1100DFE4993C
MSI (s) (08:18) [22:48:49:327]: Note: 1: 2205 2:  3: ActionText 
Action ended 22:48:49: setPermitsToLogFolder.E6E6A000_274B_4499_9314_1587794DB59B. Return value 1.
Action start 22:48:49: setPermitsToLogFolder.B7CF4EA4_7FB9_41F3_BE44_1100DFE4993C.
MSI (s) (08:18) [22:48:49:327]: Skipping action: DeleteTask.B7CF4EA4_7FB9_41F3_BE44_1100DFE4993C (condition is false)
MSI (s) (08:18) [22:48:49:327]: Skipping action: ImportTask.B7CF4EA4_7FB9_41F3_BE44_1100DFE4993C (condition is false)
MSI (s) (08:18) [22:48:49:327]: Skipping action: AlterTask.B7CF4EA4_7FB9_41F3_BE44_1100DFE4993C (condition is false)
MSI (s) (08:18) [22:48:49:327]: Doing action: InstallFinalize
MSI (s) (08:18) [22:48:49:327]: Note: 1: 2205 2:  3: ActionText 
Action ended 22:48:49: setPermitsToLogFolder.B7CF4EA4_7FB9_41F3_BE44_1100DFE4993C. Return value 1.
MSI (s) (08:18) [22:48:49:327]: Running Script: C:\Windows\Installer\MSI1ACC.tmp
MSI (s) (08:18) [22:48:49:327]: PROPERTY CHANGE: Adding UpdateStarted property. Its value is '1'.
MSI (s) (08:18) [22:48:49:327]: Note: 1: 2265 2:  3: -2147287035 
MSI (s) (08:18) [22:48:49:327]: Machine policy value 'DisableRollback' is 0
MSI (s) (08:18) [22:48:49:327]: Note: 1: 1402 2: HKEY_LOCAL_MACHINE\Software\Microsoft\Windows\CurrentVersion\Installer\Rollback\Scripts 3: 2 
MSI (s) (08:18) [22:48:49:327]: Executing op: Header(Signature=1397708873,Version=500,Timestamp=1360770585,LangId=1033,Platform=589824,ScriptType=1,ScriptMajorVersion=21,ScriptMinorVersion=4,ScriptAttributes=1)
Action start 22:48:49: InstallFinalize.
MSI (s) (08:18) [22:48:49:327]: Executing op: ProductInfo(ProductKey={75FE588B-F158-4BB3-A283-A8D18E522A52},ProductName=Intel® Trusted Connect Service Client,PackageName=iclsClientInstaller_x64.msi,Language=1033,Version=19595565,Assignment=1,ObsoleteArg=0,,,PackageCode={D68DAAC9-CC55-4F63-9734-824A80A3E1FE},,,InstanceType=0,LUASetting=0,RemoteURTInstalls=0,ProductDeploymentFlags=3)
MSI (s) (08:18) [22:48:49:327]: Executing op: DialogInfo(Type=0,Argument=1033)
MSI (s) (08:18) [22:48:49:327]: Executing op: DialogInfo(Type=1,Argument=Intel® Trusted Connect Service Client)
MSI (s) (08:18) [22:48:49:327]: Executing op: RollbackInfo(,RollbackAction=Rollback,RollbackDescription=Rolling back action:,RollbackTemplate=[1],CleanupAction=RollbackCleanup,CleanupDescription=Removing backup files,CleanupTemplate=File: [1])
MSI (s) (08:18) [22:48:49:327]: Executing op: SetBaseline(Baseline=0,)
MSI (s) (08:18) [22:48:49:327]: Executing op: SetBaseline(Baseline=1,)
MSI (s) (08:18) [22:48:49:327]: Executing op: ActionStart(Name=ProcessComponents,Description=Updating component registration,)
MSI (s) (08:18) [22:48:49:327]: Executing op: ProgressTotal(Total=22,Type=1,ByteEquivalent=24000)
MSI (s) (08:18) [22:48:49:327]: Executing op: ComponentRegister(ComponentId={89F031FB-982F-4489-83D0-0A68A49E125C},KeyPath=C:\Program Files\Intel\iCLS Client\EPIDGroupCertX509.cer,State=3,,Disk=1,SharedDllRefCount=0,BinaryType=1)
MSI (s) (08:18) [22:48:49:327]: Executing op: ComponentRegister(ComponentId={5A6F5B73-6427-4A41-A05C-B60A56C0B32F},KeyPath=C:\Program Files\Intel\iCLS Client\License.txt,State=3,,Disk=1,SharedDllRefCount=0,BinaryType=1)
MSI (s) (08:18) [22:48:49:327]: Executing op: ComponentRegister(ComponentId={464843E0-BFCB-44E5-A41F-960721443509},KeyPath=C:\Program Files\Intel\iCLS Client\iclsClient.dll,State=3,,Disk=1,SharedDllRefCount=0,BinaryType=1)
MSI (s) (08:18) [22:48:49:327]: Executing op: ComponentRegister(ComponentId={2E571CB4-F2AB-464A-B195-42827B039DB5},KeyPath=C:\Program Files\Intel\iCLS Client\iclsProxy.dll,State=3,,Disk=1,SharedDllRefCount=0,BinaryType=1)
MSI (s) (08:18) [22:48:49:327]: Executing op: ComponentRegister(ComponentId={4FF76D94-3F39-450C-B1A1-BEA689B93A9F},KeyPath=C:\Program Files\Intel\iCLS Client\libeay32.dll,State=3,,Disk=1,SharedDllRefCount=0,BinaryType=1)
MSI (s) (08:18) [22:48:49:327]: Executing op: ComponentRegister(ComponentId={1A8253A8-170A-45B5-9681-C51C814A36B7},KeyPath=22:\Software\Intel\iCLS Client\InstallDir,State=3,,Disk=1,SharedDllRefCount=0,BinaryType=1)
MSI (s) (08:18) [22:48:49:327]: Executing op: ComponentRegister(ComponentId={2A286026-951B-414B-A54C-DF43511A4234},KeyPath=C:\Program Files\Intel\iCLS Client\SocketHeciServer.conf,State=3,,Disk=1,SharedDllRefCount=0,BinaryType=1)
MSI (s) (08:18) [22:48:49:327]: Executing op: ComponentRegister(ComponentId={8009206D-F718-4338-B4F1-A48BA0780895},KeyPath=C:\Program Files\Intel\iCLS Client\SocketHeciServer.exe,State=3,,Disk=1,SharedDllRefCount=0,BinaryType=1)
MSI (s) (08:18) [22:48:49:327]: Executing op: ComponentRegister(ComponentId={3718AC6F-B76D-464E-8DA7-9BCA3DFBD187},KeyPath=C:\Windows\SysWOW64\IusEventLog.dll,State=3,,Disk=1,SharedDllRefCount=1,BinaryType=1)
MSI (s) (08:18) [22:48:49:327]: Executing op: ComponentRegister(ComponentId={3718AC6F-B76D-464E-8DA7-9BCA3DFBD187},KeyPath=C:\Windows\SysWOW64\IusEventLog.dll,State=3,ProductKey={00000000-0000-0000-0000-000000000000},Disk=1,SharedDllRefCount=1,BinaryType=1)
MSI (s) (08:18) [22:48:49:327]: Executing op: ComponentRegister(ComponentId={CBC4484B-5F24-4472-BE92-197F77AE39D3},KeyPath=D:\,State=3,,Disk=1,SharedDllRefCount=0,BinaryType=0)
MSI (s) (08:18) [22:48:49:327]: Executing op: ComponentRegister(ComponentId={CE3D72DD-D287-4AD5-8B60-C9EB699A1ACA},KeyPath=C:\Program Files\Intel\iCLS Client\IntelPTTEKRecertification.conf,State=3,,Disk=1,SharedDllRefCount=0,BinaryType=1)
MSI (s) (08:18) [22:48:49:327]: Executing op: ComponentRegister(ComponentId={6A7DAC55-CBCE-4742-82DC-6E7D02C59F4C},KeyPath=C:\Program Files\Intel\iCLS Client\IntelPTTEKRecertification.exe,State=3,,Disk=1,SharedDllRefCount=0,BinaryType=1)
MSI (s) (08:18) [22:48:49:327]: Executing op: ComponentRegister(ComponentId={C6F072DC-698B-4420-A00B-DA19D514A739},KeyPath=C:\Program Files\Intel\iCLS Client\EkRecertificationTask.xml,State=3,,Disk=1,SharedDllRefCount=0,BinaryType=1)
MSI (s) (08:18) [22:48:49:327]: Executing op: ComponentRegister(ComponentId={810482DE-5F2B-4AAD-ABAA-209D152342D2},KeyPath=C:\Program Files (x86)\Intel\iCLS Client\EPIDGroupCertX509.cer,State=3,,Disk=1,SharedDllRefCount=0,BinaryType=0)
MSI (s) (08:18) [22:48:49:343]: WIN64DUALFOLDERS: Substitution in 'C:\Program Files (x86)\Intel\iCLS Client\EPIDGroupCertX509.cer' folder had been blocked by the 1 mask argument (the folder pair's iSwapAttrib member = 0).
MSI (s) (08:18) [22:48:49:343]: Executing op: ComponentRegister(ComponentId={708CFDE2-4B9A-49E8-BE09-1E72889EBC70},KeyPath=C:\Program Files (x86)\Intel\iCLS Client\License.txt,State=3,,Disk=1,SharedDllRefCount=0,BinaryType=0)
MSI (s) (08:18) [22:48:49:343]: WIN64DUALFOLDERS: Substitution in 'C:\Program Files (x86)\Intel\iCLS Client\License.txt' folder had been blocked by the 1 mask argument (the folder pair's iSwapAttrib member = 0).
MSI (s) (08:18) [22:48:49:343]: Executing op: ComponentRegister(ComponentId={4ACF94F7-B5D1-4E1D-BF73-40BEA7E4BDA1},KeyPath=C:\Program Files (x86)\Intel\iCLS Client\iclsClient.dll,State=3,,Disk=1,SharedDllRefCount=0,BinaryType=0)
MSI (s) (08:18) [22:48:49:343]: WIN64DUALFOLDERS: Substitution in 'C:\Program Files (x86)\Intel\iCLS Client\iclsClient.dll' folder had been blocked by the 1 mask argument (the folder pair's iSwapAttrib member = 0).
MSI (s) (08:18) [22:48:49:343]: Executing op: ComponentRegister(ComponentId={C26A92A9-E868-4316-94EB-0DA018D9AF5A},KeyPath=C:\Program Files (x86)\Intel\iCLS Client\iclsProxy.dll,State=3,,Disk=1,SharedDllRefCount=0,BinaryType=0)
MSI (s) (08:18) [22:48:49:343]: WIN64DUALFOLDERS: Substitution in 'C:\Program Files (x86)\Intel\iCLS Client\iclsProxy.dll' folder had been blocked by the 1 mask argument (the folder pair's iSwapAttrib member = 0).
MSI (s) (08:18) [22:48:49:343]: Executing op: ComponentRegister(ComponentId={32F020D7-D16A-4845-B357-88559C4EF525},KeyPath=C:\Program Files (x86)\Intel\iCLS Client\libeay32.dll,State=3,,Disk=1,SharedDllRefCount=0,BinaryType=0)
MSI (s) (08:18) [22:48:49:343]: WIN64DUALFOLDERS: Substitution in 'C:\Program Files (x86)\Intel\iCLS Client\libeay32.dll' folder had been blocked by the 1 mask argument (the folder pair's iSwapAttrib member = 0).
MSI (s) (08:18) [22:48:49:343]: Executing op: ComponentRegister(ComponentId={7E89762F-F408-4189-8DC9-0FB66AFB19FC},KeyPath=02:\Software\Intel\iCLS Client\InstallDir,State=3,,Disk=1,SharedDllRefCount=0,BinaryType=0)
MSI (s) (08:18) [22:48:49:343]: Executing op: ComponentRegister(ComponentId={BAB3BB2B-0601-48E9-BD6F-B1790B3A1A18},KeyPath=C:\Program Files (x86)\Intel\iCLS Client\IntelPTTEKRecertification.conf,State=3,,Disk=1,SharedDllRefCount=0,BinaryType=0)
MSI (s) (08:18) [22:48:49:343]: WIN64DUALFOLDERS: Substitution in 'C:\Program Files (x86)\Intel\iCLS Client\IntelPTTEKRecertification.conf' folder had been blocked by the 1 mask argument (the folder pair's iSwapAttrib member = 0).
MSI (s) (08:18) [22:48:49:343]: Executing op: ComponentRegister(ComponentId={1BB32744-2FEB-41B3-8EEA-1F610F8F9277},KeyPath=C:\Program Files (x86)\Intel\iCLS Client\IntelPTTEKRecertification.exe,State=3,,Disk=1,SharedDllRefCount=0,BinaryType=0)
MSI (s) (08:18) [22:48:49:343]: WIN64DUALFOLDERS: Substitution in 'C:\Program Files (x86)\Intel\iCLS Client\IntelPTTEKRecertification.exe' folder had been blocked by the 1 mask argument (the folder pair's iSwapAttrib member = 0).
MSI (s) (08:18) [22:48:49:343]: Executing op: ComponentRegister(ComponentId={BE4F9EA4-FF91-4B58-BC2E-32F9FE008381},KeyPath=C:\Program Files (x86)\Intel\iCLS Client\EkRecertificationTask.xml,State=3,,Disk=1,SharedDllRefCount=0,BinaryType=0)
MSI (s) (08:18) [22:48:49:343]: WIN64DUALFOLDERS: Substitution in 'C:\Program Files (x86)\Intel\iCLS Client\EkRecertificationTask.xml' folder had been blocked by the 1 mask argument (the folder pair's iSwapAttrib member = 0).
MSI (s) (08:18) [22:48:49:343]: Executing op: ProgressTotal(Total=1,Type=1,ByteEquivalent=13200)
MSI (s) (08:18) [22:48:49:343]: Executing op: RegOpenKey(Root=-2147483646,Key=SOFTWARE\Microsoft\Windows\CurrentVersion\SharedDLLs,,BinaryType=1,,)
MSI (s) (08:18) [22:48:49:343]: Executing op: ProgressTick()
MSI (s) (08:18) [22:48:49:343]: Executing op: ActionStart(Name=StopServices,Description=Stopping services,Template=Service: [1])
MSI (s) (08:18) [22:48:49:343]: Executing op: ProgressTotal(Total=1,Type=1,ByteEquivalent=1300000)
MSI (s) (08:18) [22:48:49:343]: Executing op: ServiceControl(,Name=Intel(R) Capability Licensing Service TCP IP Interface,Action=2,Wait=1,)
MSI (s) (08:18) [22:48:49:343]: Executing op: ActionStart(Name=DeleteServices,Description=Deleting services,Template=Service: [1])
MSI (s) (08:18) [22:48:49:343]: Executing op: ProgressTotal(Total=1,Type=1,ByteEquivalent=1300000)
MSI (s) (08:18) [22:48:49:343]: Executing op: ServiceControl(,Name=Intel(R) Capability Licensing Service TCP IP Interface,Action=8,Wait=1,)
MSI (s) (08:18) [22:48:49:343]: Executing op: ActionStart(Name=CreateFolders,Description=Creating folders,Template=Folder: [1])
MSI (s) (08:18) [22:48:49:343]: Executing op: FolderCreate(Folder=D:\,Foreign=0,,)
MSI (s) (08:18) [22:48:49:343]: Executing op: FolderCreate(Folder=C:\ProgramData\Intel\iCLS Client\,Foreign=0,,)
MSI (s) (08:18) [22:48:49:343]: Executing op: FolderCreate(Folder=C:\ProgramData\Intel\iCLS Client\,Foreign=0,,)
MSI (s) (08:18) [22:48:49:343]: Executing op: FolderCreate(Folder=C:\ProgramData\Intel\iCLS Client\,Foreign=0,,)
MSI (s) (08:18) [22:48:49:343]: Executing op: FolderCreate(Folder=C:\ProgramData\Intel\iCLS Client\,Foreign=0,,)
MSI (s) (08:18) [22:48:49:343]: Executing op: FolderCreate(Folder=C:\ProgramData\Intel\iCLS Client\,Foreign=0,,)
MSI (s) (08:18) [22:48:49:343]: Executing op: ActionStart(Name=InstallFiles,Description=Copying new files,Template=File: [1],  Directory: [9],  Size: [6])
MSI (s) (08:18) [22:48:49:343]: Executing op: ProgressTotal(Total=24506168,Type=0,ByteEquivalent=1)
MSI (s) (08:18) [22:48:49:343]: Executing op: SetTargetFolder(Folder=C:\Program Files (x86)\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:343]: Executing op: SetSourceFolder(Folder=1\kqgfndz6\Intel\pik-g4lv\|Programs86\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:343]: Executing op: ChangeMedia(,MediaPrompt=Please insert the disk: ,MediaCabinet=iclsClient.cab,BytesPerTick=65536,CopierType=2,ModuleFileName=C:\Windows\Installer\f19e4eb.msi,,,,,IsFirstPhysicalMedia=1)
MSI (s) (08:18) [22:48:49:343]: Executing op: FileCopy(SourceName=cacert.pem,SourceCabKey=cacert.pem.E6E6A000_274B_4499_9314_1587794DB59B,DestName=cacert.pem,Attributes=512,FileSize=65595,PerTick=65536,,VerifyMedia=1,,,,,CheckCRC=0,,,InstallMode=59768832,HashOptions=0,HashPart1=1397938206,HashPart2=313732595,HashPart3=1838561442,HashPart4=50961867,,)
MSI (s) (08:18) [22:48:49:343]: File: C:\Program Files (x86)\Intel\iCLS Client\cacert.pem;	To be installed;	Won't patch;	No existing file
MSI (s) (08:18) [22:48:49:343]: Source for file 'cacert.pem.E6E6A000_274B_4499_9314_1587794DB59B' is compressed
MSI (s) (08:18) [22:48:49:343]: Executing op: SetTargetFolder(Folder=C:\Program Files\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:343]: Executing op: SetSourceFolder(Folder=1\Programs\Intel\ezrwt5wz\|Programs\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:343]: Executing op: FileCopy(SourceName=cacert.pem,SourceCabKey=cacert.pem_x64.8994F7B6_3CCC_48D6_890A_09EEEA149781,DestName=cacert.pem,Attributes=512,FileSize=65595,PerTick=65536,,VerifyMedia=1,,,,,CheckCRC=0,,,InstallMode=59768832,HashOptions=0,HashPart1=1397938206,HashPart2=313732595,HashPart3=1838561442,HashPart4=50961867,,)
MSI (s) (08:18) [22:48:49:343]: File: C:\Program Files\Intel\iCLS Client\cacert.pem;	To be installed;	Won't patch;	No existing file
MSI (s) (08:18) [22:48:49:343]: Source for file 'cacert.pem_x64.8994F7B6_3CCC_48D6_890A_09EEEA149781' is compressed
MSI (s) (08:18) [22:48:49:343]: Executing op: SetTargetFolder(Folder=C:\Program Files\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:343]: Executing op: SetSourceFolder(Folder=1\Programs\Intel\ezrwt5wz\|Programs\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:343]: Executing op: FileCopy(SourceName=uet7qdkp.xml|EkRecertificationTask.xml,SourceCabKey=EkRecertificationTask.xml.199BDD9A_24A6_4823_97EE_2CE1ACDA55D5,DestName=EkRecertificationTask.xml,Attributes=512,FileSize=7026,PerTick=65536,,VerifyMedia=1,,,,,CheckCRC=0,,,InstallMode=59768832,HashOptions=0,HashPart1=-342320674,HashPart2=1093933099,HashPart3=-1566932280,HashPart4=1569099820,,)
MSI (s) (08:18) [22:48:49:343]: File: C:\Program Files\Intel\iCLS Client\EkRecertificationTask.xml;	To be installed;	Won't patch;	No existing file
MSI (s) (08:18) [22:48:49:343]: Source for file 'EkRecertificationTask.xml.199BDD9A_24A6_4823_97EE_2CE1ACDA55D5' is compressed
MSI (s) (08:18) [22:48:49:358]: Executing op: SetTargetFolder(Folder=C:\Program Files (x86)\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:358]: Executing op: SetSourceFolder(Folder=1\kqgfndz6\Intel\pik-g4lv\|Programs86\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:358]: Executing op: FileCopy(SourceName=pbsej801.xml|EkRecertificationTask.xml,SourceCabKey=EkRecertificationTask.xml.B7CF4EA4_7FB9_41F3_BE44_1100DFE4993C,DestName=EkRecertificationTask.xml,Attributes=512,FileSize=7026,PerTick=65536,,VerifyMedia=1,,,,,CheckCRC=0,,,InstallMode=59768832,HashOptions=0,HashPart1=-342320674,HashPart2=1093933099,HashPart3=-1566932280,HashPart4=1569099820,,)
MSI (s) (08:18) [22:48:49:358]: File: C:\Program Files (x86)\Intel\iCLS Client\EkRecertificationTask.xml;	To be installed;	Won't patch;	No existing file
MSI (s) (08:18) [22:48:49:358]: Source for file 'EkRecertificationTask.xml.B7CF4EA4_7FB9_41F3_BE44_1100DFE4993C' is compressed
MSI (s) (08:18) [22:48:49:358]: Executing op: SetTargetFolder(Folder=C:\Program Files\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:358]: Executing op: SetSourceFolder(Folder=1\Programs\Intel\ezrwt5wz\|Programs\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:358]: Executing op: FileCopy(SourceName=6xcatwh-.dat|epid_paramcert.dat,SourceCabKey=epid_paramcert_x64.8994F7B6_3CCC_48D6_890A_09EEEA149781,DestName=epid_paramcert.dat,Attributes=512,FileSize=876,PerTick=65536,,VerifyMedia=1,,,,,CheckCRC=0,,,InstallMode=59768832,HashOptions=0,HashPart1=1983947846,HashPart2=1291112792,HashPart3=1273000713,HashPart4=177938096,,)
MSI (s) (08:18) [22:48:49:358]: File: C:\Program Files\Intel\iCLS Client\epid_paramcert.dat;	To be installed;	Won't patch;	No existing file
MSI (s) (08:18) [22:48:49:358]: Source for file 'epid_paramcert_x64.8994F7B6_3CCC_48D6_890A_09EEEA149781' is compressed
MSI (s) (08:18) [22:48:49:358]: Executing op: SetTargetFolder(Folder=C:\Program Files (x86)\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:358]: Executing op: SetSourceFolder(Folder=1\kqgfndz6\Intel\pik-g4lv\|Programs86\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:358]: Executing op: FileCopy(SourceName=6xcatwh-.dat|epid_paramcert.dat,SourceCabKey=epid_paramcert_x86.E6E6A000_274B_4499_9314_1587794DB59B,DestName=epid_paramcert.dat,Attributes=512,FileSize=876,PerTick=65536,,VerifyMedia=1,,,,,CheckCRC=0,,,InstallMode=59768832,HashOptions=0,HashPart1=1983947846,HashPart2=1291112792,HashPart3=1273000713,HashPart4=177938096,,)
MSI (s) (08:18) [22:48:49:358]: File: C:\Program Files (x86)\Intel\iCLS Client\epid_paramcert.dat;	To be installed;	Won't patch;	No existing file
MSI (s) (08:18) [22:48:49:358]: Source for file 'epid_paramcert_x86.E6E6A000_274B_4499_9314_1587794DB59B' is compressed
MSI (s) (08:18) [22:48:49:358]: Executing op: SetTargetFolder(Folder=C:\Program Files\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:358]: Executing op: SetSourceFolder(Folder=1\Programs\Intel\ezrwt5wz\|Programs\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:358]: Executing op: FileCopy(SourceName=a0h_yrub.cer|EPIDGroupCertLegacy.cer,SourceCabKey=EPIDGroupCertLegacy_x64.8994F7B6_3CCC_48D6_890A_09EEEA149781,DestName=EPIDGroupCertLegacy.cer,Attributes=512,FileSize=1549968,PerTick=65536,,VerifyMedia=1,,,,,CheckCRC=0,,,InstallMode=59768832,HashOptions=0,HashPart1=-1480926534,HashPart2=481921965,HashPart3=1391730588,HashPart4=2147387991,,)
MSI (s) (08:18) [22:48:49:358]: File: C:\Program Files\Intel\iCLS Client\EPIDGroupCertLegacy.cer;	To be installed;	Won't patch;	No existing file
MSI (s) (08:18) [22:48:49:358]: Source for file 'EPIDGroupCertLegacy_x64.8994F7B6_3CCC_48D6_890A_09EEEA149781' is compressed
MSI (s) (08:18) [22:48:49:358]: Executing op: SetTargetFolder(Folder=C:\Program Files (x86)\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:358]: Executing op: SetSourceFolder(Folder=1\kqgfndz6\Intel\pik-g4lv\|Programs86\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:358]: Executing op: FileCopy(SourceName=a0h_yrub.cer|EPIDGroupCertLegacy.cer,SourceCabKey=EPIDGroupCertLegacy_x86.E6E6A000_274B_4499_9314_1587794DB59B,DestName=EPIDGroupCertLegacy.cer,Attributes=512,FileSize=1549968,PerTick=65536,,VerifyMedia=1,,,,,CheckCRC=0,,,InstallMode=59768832,HashOptions=0,HashPart1=-1480926534,HashPart2=481921965,HashPart3=1391730588,HashPart4=2147387991,,)
MSI (s) (08:18) [22:48:49:358]: File: C:\Program Files (x86)\Intel\iCLS Client\EPIDGroupCertLegacy.cer;	To be installed;	Won't patch;	No existing file
MSI (s) (08:18) [22:48:49:358]: Source for file 'EPIDGroupCertLegacy_x86.E6E6A000_274B_4499_9314_1587794DB59B' is compressed
MSI (s) (08:18) [22:48:49:374]: Executing op: SetTargetFolder(Folder=C:\Program Files\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:374]: Executing op: SetSourceFolder(Folder=1\Programs\Intel\ezrwt5wz\|Programs\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:374]: Executing op: FileCopy(SourceName=jqyejyzc.cer|EPIDGroupCertX509.cer,SourceCabKey=EPIDGroupCertX509_x64.8994F7B6_3CCC_48D6_890A_09EEEA149781,DestName=EPIDGroupCertX509.cer,Attributes=512,FileSize=2924159,PerTick=65536,,VerifyMedia=1,,,,,CheckCRC=0,,,InstallMode=59768832,HashOptions=0,HashPart1=-1931081484,HashPart2=1100690121,HashPart3=2057599293,HashPart4=-1337252334,,)
MSI (s) (08:18) [22:48:49:374]: File: C:\Program Files\Intel\iCLS Client\EPIDGroupCertX509.cer;	To be installed;	Won't patch;	No existing file
MSI (s) (08:18) [22:48:49:374]: Source for file 'EPIDGroupCertX509_x64.8994F7B6_3CCC_48D6_890A_09EEEA149781' is compressed
MSI (s) (08:18) [22:48:49:390]: Executing op: SetTargetFolder(Folder=C:\Program Files (x86)\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:390]: Executing op: SetSourceFolder(Folder=1\kqgfndz6\Intel\pik-g4lv\|Programs86\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:390]: Executing op: FileCopy(SourceName=jqyejyzc.cer|EPIDGroupCertX509.cer,SourceCabKey=EPIDGroupCertX509_x86.E6E6A000_274B_4499_9314_1587794DB59B,DestName=EPIDGroupCertX509.cer,Attributes=512,FileSize=2924159,PerTick=65536,,VerifyMedia=1,,,,,CheckCRC=0,,,InstallMode=59768832,HashOptions=0,HashPart1=-1931081484,HashPart2=1100690121,HashPart3=2057599293,HashPart4=-1337252334,,)
MSI (s) (08:18) [22:48:49:390]: File: C:\Program Files (x86)\Intel\iCLS Client\EPIDGroupCertX509.cer;	To be installed;	Won't patch;	No existing file
MSI (s) (08:18) [22:48:49:390]: Source for file 'EPIDGroupCertX509_x86.E6E6A000_274B_4499_9314_1587794DB59B' is compressed
MSI (s) (08:18) [22:48:49:405]: Executing op: FileCopy(SourceName=9lvqww8s.dll|iclsClient.dll,SourceCabKey=iclsClientDll.E6E6A000_274B_4499_9314_1587794DB59B,DestName=iclsClient.dll,Attributes=512,FileSize=282904,PerTick=65536,,VerifyMedia=1,,,,,CheckCRC=0,Version=1.43.301.1,Language=1033,InstallMode=59768832,,,,,,,)
MSI (s) (08:18) [22:48:49:405]: File: C:\Program Files (x86)\Intel\iCLS Client\iclsClient.dll;	To be installed;	Won't patch;	No existing file
MSI (s) (08:18) [22:48:49:405]: Source for file 'iclsClientDll.E6E6A000_274B_4499_9314_1587794DB59B' is compressed
MSI (s) (08:18) [22:48:49:405]: Executing op: SetTargetFolder(Folder=C:\Program Files\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:405]: Executing op: SetSourceFolder(Folder=1\Programs\Intel\ezrwt5wz\|Programs\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:405]: Executing op: FileCopy(SourceName=cinxbihj.dll|iclsClient.dll,SourceCabKey=iclsClientDll_x64.8994F7B6_3CCC_48D6_890A_09EEEA149781,DestName=iclsClient.dll,Attributes=512,FileSize=388888,PerTick=65536,,VerifyMedia=1,,,,,CheckCRC=0,Version=1.43.301.1,Language=1033,InstallMode=59768832,,,,,,,)
MSI (s) (08:18) [22:48:49:405]: File: C:\Program Files\Intel\iCLS Client\iclsClient.dll;	To be installed;	Won't patch;	No existing file
MSI (s) (08:18) [22:48:49:405]: Source for file 'iclsClientDll_x64.8994F7B6_3CCC_48D6_890A_09EEEA149781' is compressed
MSI (s) (08:18) [22:48:49:405]: Executing op: SetTargetFolder(Folder=C:\Program Files (x86)\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:405]: Executing op: SetSourceFolder(Folder=1\kqgfndz6\Intel\pik-g4lv\|Programs86\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:405]: Executing op: FileCopy(SourceName=xt5xy8td.dll|iclsClientInternal.dll,SourceCabKey=iclsClientInternalDll.E6E6A000_274B_4499_9314_1587794DB59B,DestName=iclsClientInternal.dll,Attributes=512,FileSize=1695528,PerTick=65536,,VerifyMedia=1,,,,,CheckCRC=0,Version=1.43.301.1,Language=1033,InstallMode=59768832,,,,,,,)
MSI (s) (08:18) [22:48:49:405]: File: C:\Program Files (x86)\Intel\iCLS Client\iclsClientInternal.dll;	To be installed;	Won't patch;	No existing file
MSI (s) (08:18) [22:48:49:405]: Source for file 'iclsClientInternalDll.E6E6A000_274B_4499_9314_1587794DB59B' is compressed
MSI (s) (08:18) [22:48:49:421]: Executing op: SetTargetFolder(Folder=C:\Program Files\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:421]: Executing op: SetSourceFolder(Folder=1\Programs\Intel\ezrwt5wz\|Programs\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:421]: Executing op: FileCopy(SourceName=q-ngaehu.dll|iclsClientInternal.dll,SourceCabKey=iclsClientInternalDll_x64.8994F7B6_3CCC_48D6_890A_09EEEA149781,DestName=iclsClientInternal.dll,Attributes=512,FileSize=2170664,PerTick=65536,,VerifyMedia=1,,,,,CheckCRC=0,Version=1.43.301.1,Language=1033,InstallMode=59768832,,,,,,,)
MSI (s) (08:18) [22:48:49:421]: File: C:\Program Files\Intel\iCLS Client\iclsClientInternal.dll;	To be installed;	Won't patch;	No existing file
MSI (s) (08:18) [22:48:49:421]: Source for file 'iclsClientInternalDll_x64.8994F7B6_3CCC_48D6_890A_09EEEA149781' is compressed
MSI (s) (08:18) [22:48:49:436]: Executing op: SetTargetFolder(Folder=C:\Program Files (x86)\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:436]: Executing op: SetSourceFolder(Folder=1\kqgfndz6\Intel\pik-g4lv\|Programs86\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:436]: Executing op: FileCopy(SourceName=tj1qyihn.con|iclsProxy.conf,SourceCabKey=iclsProxyConf.E6E6A000_274B_4499_9314_1587794DB59B,DestName=iclsProxy.conf,Attributes=512,FileSize=1969,PerTick=65536,,VerifyMedia=1,,,,,CheckCRC=0,,,InstallMode=59768832,HashOptions=0,HashPart1=-809888198,HashPart2=937016403,HashPart3=1607387639,HashPart4=-1479141078,,)
MSI (s) (08:18) [22:48:49:436]: File: C:\Program Files (x86)\Intel\iCLS Client\iclsProxy.conf;	To be installed;	Won't patch;	No existing file
MSI (s) (08:18) [22:48:49:436]: Source for file 'iclsProxyConf.E6E6A000_274B_4499_9314_1587794DB59B' is compressed
MSI (s) (08:18) [22:48:49:436]: Executing op: SetTargetFolder(Folder=C:\Program Files\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:436]: Executing op: SetSourceFolder(Folder=1\Programs\Intel\ezrwt5wz\|Programs\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:436]: Executing op: FileCopy(SourceName=lfvbvhf6.con|iclsProxy.conf,SourceCabKey=iclsProxyConf_x64.8994F7B6_3CCC_48D6_890A_09EEEA149781,DestName=iclsProxy.conf,Attributes=512,FileSize=1969,PerTick=65536,,VerifyMedia=1,,,,,CheckCRC=0,,,InstallMode=59768832,HashOptions=0,HashPart1=-809888198,HashPart2=937016403,HashPart3=1607387639,HashPart4=-1479141078,,)
MSI (s) (08:18) [22:48:49:436]: File: C:\Program Files\Intel\iCLS Client\iclsProxy.conf;	To be installed;	Won't patch;	No existing file
MSI (s) (08:18) [22:48:49:436]: Source for file 'iclsProxyConf_x64.8994F7B6_3CCC_48D6_890A_09EEEA149781' is compressed
MSI (s) (08:18) [22:48:49:436]: Executing op: SetTargetFolder(Folder=C:\Program Files (x86)\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:436]: Executing op: SetSourceFolder(Folder=1\kqgfndz6\Intel\pik-g4lv\|Programs86\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:436]: Executing op: FileCopy(SourceName=9ddyo760.dll|iclsProxy.dll,SourceCabKey=iclsProxyDll.E6E6A000_274B_4499_9314_1587794DB59B,DestName=iclsProxy.dll,Attributes=512,FileSize=299800,PerTick=65536,,VerifyMedia=1,,,,,CheckCRC=0,Version=1.43.301.1,Language=1033,InstallMode=59768832,,,,,,,)
MSI (s) (08:18) [22:48:49:436]: File: C:\Program Files (x86)\Intel\iCLS Client\iclsProxy.dll;	To be installed;	Won't patch;	No existing file
MSI (s) (08:18) [22:48:49:436]: Source for file 'iclsProxyDll.E6E6A000_274B_4499_9314_1587794DB59B' is compressed
MSI (s) (08:18) [22:48:49:436]: Executing op: SetTargetFolder(Folder=C:\Program Files\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:436]: Executing op: SetSourceFolder(Folder=1\Programs\Intel\ezrwt5wz\|Programs\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:436]: Executing op: FileCopy(SourceName=c571kv_m.dll|iclsProxy.dll,SourceCabKey=iclsProxyDll_x64.8994F7B6_3CCC_48D6_890A_09EEEA149781,DestName=iclsProxy.dll,Attributes=512,FileSize=409880,PerTick=65536,,VerifyMedia=1,,,,,CheckCRC=0,Version=1.43.301.1,Language=1033,InstallMode=59768832,,,,,,,)
MSI (s) (08:18) [22:48:49:436]: File: C:\Program Files\Intel\iCLS Client\iclsProxy.dll;	To be installed;	Won't patch;	No existing file
MSI (s) (08:18) [22:48:49:436]: Source for file 'iclsProxyDll_x64.8994F7B6_3CCC_48D6_890A_09EEEA149781' is compressed
MSI (s) (08:18) [22:48:49:436]: Executing op: SetTargetFolder(Folder=C:\Program Files (x86)\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:436]: Executing op: SetSourceFolder(Folder=1\kqgfndz6\Intel\pik-g4lv\|Programs86\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:436]: Executing op: FileCopy(SourceName=uuqxybk2.dll|iclsProxyInternal.dll,SourceCabKey=iclsProxyInternalDll.E6E6A000_274B_4499_9314_1587794DB59B,DestName=iclsProxyInternal.dll,Attributes=512,FileSize=1360680,PerTick=65536,,VerifyMedia=1,,,,,CheckCRC=0,Version=1.43.301.1,Language=1033,InstallMode=59768832,,,,,,,)
MSI (s) (08:18) [22:48:49:436]: File: C:\Program Files (x86)\Intel\iCLS Client\iclsProxyInternal.dll;	To be installed;	Won't patch;	No existing file
MSI (s) (08:18) [22:48:49:436]: Source for file 'iclsProxyInternalDll.E6E6A000_274B_4499_9314_1587794DB59B' is compressed
MSI (s) (08:18) [22:48:49:452]: Executing op: SetTargetFolder(Folder=C:\Program Files\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:452]: Executing op: SetSourceFolder(Folder=1\Programs\Intel\ezrwt5wz\|Programs\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:452]: Executing op: FileCopy(SourceName=qiauuxmm.dll|iclsProxyInternal.dll,SourceCabKey=iclsProxyInternalDll_x64.8994F7B6_3CCC_48D6_890A_09EEEA149781,DestName=iclsProxyInternal.dll,Attributes=512,FileSize=1829160,PerTick=65536,,VerifyMedia=1,,,,,CheckCRC=0,Version=1.43.301.1,Language=1033,InstallMode=59768832,,,,,,,)
MSI (s) (08:18) [22:48:49:452]: File: C:\Program Files\Intel\iCLS Client\iclsProxyInternal.dll;	To be installed;	Won't patch;	No existing file
MSI (s) (08:18) [22:48:49:452]: Source for file 'iclsProxyInternalDll_x64.8994F7B6_3CCC_48D6_890A_09EEEA149781' is compressed
MSI (s) (08:18) [22:48:49:468]: Executing op: SetTargetFolder(Folder=C:\Program Files\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:468]: Executing op: SetSourceFolder(Folder=1\Programs\Intel\ezrwt5wz\|Programs\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:468]: Executing op: FileCopy(SourceName=76htkk8y.con|IntelPTTEKRecertification.conf,SourceCabKey=IntelPTTEKRecertification.conf.199BDD9A_24A6_4823_97EE_2CE1ACDA55D5,DestName=IntelPTTEKRecertification.conf,Attributes=512,FileSize=823,PerTick=65536,,VerifyMedia=1,,,,,CheckCRC=0,,,InstallMode=59768832,HashOptions=0,HashPart1=-131269312,HashPart2=-1262851006,HashPart3=1786214345,HashPart4=-626572402,,)
MSI (s) (08:18) [22:48:49:468]: File: C:\Program Files\Intel\iCLS Client\IntelPTTEKRecertification.conf;	To be installed;	Won't patch;	No existing file
MSI (s) (08:18) [22:48:49:468]: Source for file 'IntelPTTEKRecertification.conf.199BDD9A_24A6_4823_97EE_2CE1ACDA55D5' is compressed
MSI (s) (08:18) [22:48:49:468]: Executing op: SetTargetFolder(Folder=C:\Program Files (x86)\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:468]: Executing op: SetSourceFolder(Folder=1\kqgfndz6\Intel\pik-g4lv\|Programs86\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:468]: Executing op: FileCopy(SourceName=z18yqs5u.con|IntelPTTEKRecertification.conf,SourceCabKey=IntelPTTEKRecertification.conf.B7CF4EA4_7FB9_41F3_BE44_1100DFE4993C,DestName=IntelPTTEKRecertification.conf,Attributes=512,FileSize=823,PerTick=65536,,VerifyMedia=1,,,,,CheckCRC=0,,,InstallMode=59768832,HashOptions=0,HashPart1=-131269312,HashPart2=-1262851006,HashPart3=1786214345,HashPart4=-626572402,,)
MSI (s) (08:18) [22:48:49:468]: File: C:\Program Files (x86)\Intel\iCLS Client\IntelPTTEKRecertification.conf;	To be installed;	Won't patch;	No existing file
MSI (s) (08:18) [22:48:49:468]: Source for file 'IntelPTTEKRecertification.conf.B7CF4EA4_7FB9_41F3_BE44_1100DFE4993C' is compressed
MSI (s) (08:18) [22:48:49:468]: Executing op: SetTargetFolder(Folder=C:\Program Files\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:468]: Executing op: SetSourceFolder(Folder=1\Programs\Intel\ezrwt5wz\|Programs\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:468]: Executing op: FileCopy(SourceName=bbu8urgo.exe|IntelPTTEKRecertification.exe,SourceCabKey=IntelPTTEKRecertification.exe_x64.199BDD9A_24A6_4823_97EE_2CE1ACDA55D5,DestName=IntelPTTEKRecertification.exe,Attributes=512,FileSize=909112,PerTick=65536,,VerifyMedia=1,,,,,CheckCRC=0,Version=1.43.301.1,Language=1033,InstallMode=59768832,,,,,,,)
MSI (s) (08:18) [22:48:49:468]: File: C:\Program Files\Intel\iCLS Client\IntelPTTEKRecertification.exe;	To be installed;	Won't patch;	No existing file
MSI (s) (08:18) [22:48:49:468]: Source for file 'IntelPTTEKRecertification.exe_x64.199BDD9A_24A6_4823_97EE_2CE1ACDA55D5' is compressed
MSI (s) (08:18) [22:48:49:483]: Executing op: SetTargetFolder(Folder=C:\Program Files (x86)\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:483]: Executing op: SetSourceFolder(Folder=1\kqgfndz6\Intel\pik-g4lv\|Programs86\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:483]: Executing op: FileCopy(SourceName=iqhzdxkv.exe|IntelPTTEKRecertification.exe,SourceCabKey=IntelPTTEKRecertification.exe_x86.B7CF4EA4_7FB9_41F3_BE44_1100DFE4993C,DestName=IntelPTTEKRecertification.exe,Attributes=512,FileSize=671032,PerTick=65536,,VerifyMedia=1,,,,,CheckCRC=0,Version=1.43.301.1,Language=1033,InstallMode=59768832,,,,,,,)
MSI (s) (08:18) [22:48:49:483]: File: C:\Program Files (x86)\Intel\iCLS Client\IntelPTTEKRecertification.exe;	To be installed;	Won't patch;	No existing file
MSI (s) (08:18) [22:48:49:483]: Source for file 'IntelPTTEKRecertification.exe_x86.B7CF4EA4_7FB9_41F3_BE44_1100DFE4993C' is compressed
MSI (s) (08:18) [22:48:49:483]: Executing op: SetTargetFolder(Folder=C:\Windows\SysWOW64\)
MSI (s) (08:18) [22:48:49:483]: Executing op: SetSourceFolder(Folder=1\Programs\Intel\ezrwt5wz\System\|Programs\Intel\iCLS Client\System\)
MSI (s) (08:18) [22:48:49:483]: Executing op: FileCopy(SourceName=0yg_ozd8.dll|IusEventLog.dll,SourceCabKey=IusEventLog.dll.9B48670B_D6C7_46FD_9AE5_24CBB7D30A26,DestName=IusEventLog.dll,Attributes=512,FileSize=11552,PerTick=65536,,VerifyMedia=1,,,,,CheckCRC=0,Version=1.43.301.1,Language=1033,InstallMode=59768832,,,,,,,)
MSI (s) (08:18) [22:48:49:483]: File: C:\Windows\SysWOW64\IusEventLog.dll;	To be installed;	Won't patch;	No existing file
MSI (s) (08:18) [22:48:49:483]: Source for file 'IusEventLog.dll.9B48670B_D6C7_46FD_9AE5_24CBB7D30A26' is compressed
MSI (s) (08:18) [22:48:49:483]: Executing op: SetTargetFolder(Folder=C:\Program Files (x86)\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:483]: Executing op: SetSourceFolder(Folder=1\kqgfndz6\Intel\pik-g4lv\|Programs86\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:483]: Executing op: FileCopy(SourceName=libeay32.dll,SourceCabKey=libeay.E6E6A000_274B_4499_9314_1587794DB59B,DestName=libeay32.dll,Attributes=512,FileSize=1374952,PerTick=65536,,VerifyMedia=1,,,,,CheckCRC=0,Version=1.0.2.8,Language=1033,InstallMode=59768832,,,,,,,)
MSI (s) (08:18) [22:48:49:483]: File: C:\Program Files (x86)\Intel\iCLS Client\libeay32.dll;	To be installed;	Won't patch;	No existing file
MSI (s) (08:18) [22:48:49:483]: Source for file 'libeay.E6E6A000_274B_4499_9314_1587794DB59B' is compressed
MSI (s) (08:18) [22:48:49:499]: Executing op: SetTargetFolder(Folder=C:\Program Files\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:499]: Executing op: SetSourceFolder(Folder=1\Programs\Intel\ezrwt5wz\|Programs\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:499]: Executing op: FileCopy(SourceName=libeay32.dll,SourceCabKey=libeay_x64.8994F7B6_3CCC_48D6_890A_09EEEA149781,DestName=libeay32.dll,Attributes=512,FileSize=2210024,PerTick=65536,,VerifyMedia=1,,,,,CheckCRC=0,Version=1.0.2.8,Language=1033,InstallMode=59768832,,,,,,,)
MSI (s) (08:18) [22:48:49:499]: File: C:\Program Files\Intel\iCLS Client\libeay32.dll;	To be installed;	Won't patch;	No existing file
MSI (s) (08:18) [22:48:49:499]: Source for file 'libeay_x64.8994F7B6_3CCC_48D6_890A_09EEEA149781' is compressed
MSI (s) (08:18) [22:48:49:515]: Executing op: FileCopy(SourceName=License.txt,SourceCabKey=license_x64.8994F7B6_3CCC_48D6_890A_09EEEA149781,DestName=License.txt,Attributes=512,FileSize=5564,PerTick=65536,,VerifyMedia=1,,,,,CheckCRC=0,,,InstallMode=59768832,HashOptions=0,HashPart1=-696015377,HashPart2=-1048901602,HashPart3=-1381849744,HashPart4=-73310313,,)
MSI (s) (08:18) [22:48:49:515]: File: C:\Program Files\Intel\iCLS Client\License.txt;	To be installed;	Won't patch;	No existing file
MSI (s) (08:18) [22:48:49:515]: Source for file 'license_x64.8994F7B6_3CCC_48D6_890A_09EEEA149781' is compressed
MSI (s) (08:18) [22:48:49:515]: Executing op: SetTargetFolder(Folder=C:\Program Files (x86)\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:515]: Executing op: SetSourceFolder(Folder=1\kqgfndz6\Intel\pik-g4lv\|Programs86\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:515]: Executing op: FileCopy(SourceName=License.txt,SourceCabKey=license_x86.E6E6A000_274B_4499_9314_1587794DB59B,DestName=License.txt,Attributes=512,FileSize=5564,PerTick=65536,,VerifyMedia=1,,,,,CheckCRC=0,,,InstallMode=59768832,HashOptions=0,HashPart1=-696015377,HashPart2=-1048901602,HashPart3=-1381849744,HashPart4=-73310313,,)
MSI (s) (08:18) [22:48:49:515]: File: C:\Program Files (x86)\Intel\iCLS Client\License.txt;	To be installed;	Won't patch;	No existing file
MSI (s) (08:18) [22:48:49:515]: Source for file 'license_x86.E6E6A000_274B_4499_9314_1587794DB59B' is compressed
MSI (s) (08:18) [22:48:49:530]: Executing op: SetTargetFolder(Folder=C:\Program Files\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:530]: Executing op: SetSourceFolder(Folder=1\Programs\Intel\ezrwt5wz\|Programs\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:530]: Executing op: FileCopy(SourceName=Readme.txt,SourceCabKey=Readme_x64.8994F7B6_3CCC_48D6_890A_09EEEA149781,DestName=Readme.txt,Attributes=512,FileSize=1087,PerTick=65536,,VerifyMedia=1,,,,,CheckCRC=0,,,InstallMode=59768832,HashOptions=0,HashPart1=377489005,HashPart2=2016952969,HashPart3=733821493,HashPart4=-1041230327,,)
MSI (s) (08:18) [22:48:49:530]: File: C:\Program Files\Intel\iCLS Client\Readme.txt;	To be installed;	Won't patch;	No existing file
MSI (s) (08:18) [22:48:49:530]: Source for file 'Readme_x64.8994F7B6_3CCC_48D6_890A_09EEEA149781' is compressed
MSI (s) (08:18) [22:48:49:530]: Executing op: SetTargetFolder(Folder=C:\Program Files (x86)\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:530]: Executing op: SetSourceFolder(Folder=1\kqgfndz6\Intel\pik-g4lv\|Programs86\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:530]: Executing op: FileCopy(SourceName=Readme.txt,SourceCabKey=Readme_x86.E6E6A000_274B_4499_9314_1587794DB59B,DestName=Readme.txt,Attributes=512,FileSize=1087,PerTick=65536,,VerifyMedia=1,,,,,CheckCRC=0,,,InstallMode=59768832,HashOptions=0,HashPart1=377489005,HashPart2=2016952969,HashPart3=733821493,HashPart4=-1041230327,,)
MSI (s) (08:18) [22:48:49:530]: File: C:\Program Files (x86)\Intel\iCLS Client\Readme.txt;	To be installed;	Won't patch;	No existing file
MSI (s) (08:18) [22:48:49:530]: Source for file 'Readme_x86.E6E6A000_274B_4499_9314_1587794DB59B' is compressed
MSI (s) (08:18) [22:48:49:530]: Executing op: SetTargetFolder(Folder=C:\Program Files\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:530]: Executing op: SetSourceFolder(Folder=1\Programs\Intel\ezrwt5wz\|Programs\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:530]: Executing op: FileCopy(SourceName=josszczf.con|SocketHeciServer.conf,SourceCabKey=SocketHeciServer.conf.9B48670B_D6C7_46FD_9AE5_24CBB7D30A26,DestName=SocketHeciServer.conf,Attributes=512,FileSize=818,PerTick=65536,,VerifyMedia=1,,,,,CheckCRC=0,,,InstallMode=59768832,HashOptions=0,HashPart1=1066992537,HashPart2=-132498554,HashPart3=632049490,HashPart4=575555462,,)
MSI (s) (08:18) [22:48:49:530]: File: C:\Program Files\Intel\iCLS Client\SocketHeciServer.conf;	To be installed;	Won't patch;	No existing file
MSI (s) (08:18) [22:48:49:530]: Source for file 'SocketHeciServer.conf.9B48670B_D6C7_46FD_9AE5_24CBB7D30A26' is compressed
MSI (s) (08:18) [22:48:49:530]: Executing op: FileCopy(SourceName=jny4qpx-.exe|SocketHeciServer.exe,SourceCabKey=SocketHeciServer.exe_x64.9B48670B_D6C7_46FD_9AE5_24CBB7D30A26,DestName=SocketHeciServer.exe,Attributes=512,FileSize=987432,PerTick=65536,,VerifyMedia=1,,,,,CheckCRC=0,Version=1.43.301.1,Language=1033,InstallMode=59768832,,,,,,,)
MSI (s) (08:18) [22:48:49:530]: File: C:\Program Files\Intel\iCLS Client\SocketHeciServer.exe;	To be installed;	Won't patch;	No existing file
MSI (s) (08:18) [22:48:49:530]: Source for file 'SocketHeciServer.exe_x64.9B48670B_D6C7_46FD_9AE5_24CBB7D30A26' is compressed
MSI (s) (08:18) [22:48:49:530]: Executing op: SetTargetFolder(Folder=C:\Program Files (x86)\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:530]: Executing op: SetSourceFolder(Folder=1\kqgfndz6\Intel\pik-g4lv\|Programs86\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:530]: Executing op: FileCopy(SourceName=ssleay32.dll,SourceCabKey=ssleay.E6E6A000_274B_4499_9314_1587794DB59B,DestName=ssleay32.dll,Attributes=512,FileSize=340200,PerTick=65536,,VerifyMedia=1,,,,,CheckCRC=0,Version=1.0.2.8,Language=1033,InstallMode=59768832,,,,,,,)
MSI (s) (08:18) [22:48:49:530]: File: C:\Program Files (x86)\Intel\iCLS Client\ssleay32.dll;	To be installed;	Won't patch;	No existing file
MSI (s) (08:18) [22:48:49:530]: Source for file 'ssleay.E6E6A000_274B_4499_9314_1587794DB59B' is compressed
MSI (s) (08:18) [22:48:49:546]: Executing op: SetTargetFolder(Folder=C:\Program Files\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:546]: Executing op: SetSourceFolder(Folder=1\Programs\Intel\ezrwt5wz\|Programs\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:546]: Executing op: FileCopy(SourceName=ssleay32.dll,SourceCabKey=ssleay_x64.8994F7B6_3CCC_48D6_890A_09EEEA149781,DestName=ssleay32.dll,Attributes=512,FileSize=423656,PerTick=65536,,VerifyMedia=1,,,,,CheckCRC=0,Version=1.0.2.8,Language=1033,InstallMode=59768832,,,,,,,)
MSI (s) (08:18) [22:48:49:546]: File: C:\Program Files\Intel\iCLS Client\ssleay32.dll;	To be installed;	Won't patch;	No existing file
MSI (s) (08:18) [22:48:49:546]: Source for file 'ssleay_x64.8994F7B6_3CCC_48D6_890A_09EEEA149781' is compressed
MSI (s) (08:18) [22:48:49:546]: Executing op: FileCopy(SourceName=falsyqv2.txt|Third Party Licenses.txt,SourceCabKey=ThirdPartyLicense_x64.8994F7B6_3CCC_48D6_890A_09EEEA149781,DestName=Third Party Licenses.txt,Attributes=512,FileSize=12876,PerTick=65536,,VerifyMedia=1,,,,,CheckCRC=0,,,InstallMode=59768832,HashOptions=0,HashPart1=-1606128101,HashPart2=-1179910107,HashPart3=881647832,HashPart4=531244984,,)
MSI (s) (08:18) [22:48:49:546]: File: C:\Program Files\Intel\iCLS Client\Third Party Licenses.txt;	To be installed;	Won't patch;	No existing file
MSI (s) (08:18) [22:48:49:546]: Source for file 'ThirdPartyLicense_x64.8994F7B6_3CCC_48D6_890A_09EEEA149781' is compressed
MSI (s) (08:18) [22:48:49:546]: Executing op: SetTargetFolder(Folder=C:\Program Files (x86)\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:546]: Executing op: SetSourceFolder(Folder=1\kqgfndz6\Intel\pik-g4lv\|Programs86\Intel\iCLS Client\)
MSI (s) (08:18) [22:48:49:546]: Executing op: FileCopy(SourceName=falsyqv2.txt|Third Party Licenses.txt,SourceCabKey=ThirdPartyLicense_x86.E6E6A000_274B_4499_9314_1587794DB59B,DestName=Third Party Licenses.txt,Attributes=512,FileSize=12876,PerTick=65536,,VerifyMedia=1,,,,,CheckCRC=0,,,InstallMode=59768832,HashOptions=0,HashPart1=-1606128101,HashPart2=-1179910107,HashPart3=881647832,HashPart4=531244984,,)
MSI (s) (08:18) [22:48:49:546]: File: C:\Program Files (x86)\Intel\iCLS Client\Third Party Licenses.txt;	To be installed;	Won't patch;	No existing file
MSI (s) (08:18) [22:48:49:546]: Source for file 'ThirdPartyLicense_x86.E6E6A000_274B_4499_9314_1587794DB59B' is compressed
MSI (s) (08:18) [22:48:49:546]: Executing op: CacheSizeFlush(,)
MSI (s) (08:18) [22:48:49:546]: Executing op: ActionStart(Name=WriteRegistryValues,Description=Writing system registry values,Template=Key: [1], Name: [2], Value: [3])
MSI (s) (08:18) [22:48:49:546]: Executing op: ProgressTotal(Total=14,Type=1,ByteEquivalent=13200)
MSI (s) (08:18) [22:48:49:546]: Executing op: RegOpenKey(Root=-2147483646,Key=Software\Intel\iCLS Client,,BinaryType=0,,)
MSI (s) (08:18) [22:48:49:546]: Executing op: RegAddValue(Name=InstallDir,Value=C:\Program Files (x86)\Intel\iCLS Client\,)
MSI (s) (08:18) [22:48:49:546]: Executing op: RegOpenKey(Root=-2147483646,Key=Software\Intel\HeciServer,,BinaryType=0,,)
MSI (s) (08:18) [22:48:49:546]: Executing op: RegAddValue(Name=SocketServiceName,Value=Intel(R) Capability Licensing Service TCP IP Interface,)
MSI (s) (08:18) [22:48:49:546]: Executing op: RegAddValue(Name=SocketServiceDisplayName,Value=Intel(R) Capability Licensing Service TCP IP Interface,)
MSI (s) (08:18) [22:48:49:546]: Executing op: RegOpenKey(Root=-2147483646,Key=Software\Intel\iCLS Client\Version,,BinaryType=0,,)
MSI (s) (08:18) [22:48:49:546]: Executing op: RegAddValue(Name=buildNumber,Value=1.43.301.1,)
MSI (s) (08:18) [22:48:49:546]: Executing op: RegAddValue(Name=API_Version,Value=#1,)
MSI (s) (08:18) [22:48:49:546]: Executing op: RegOpenKey(Root=-2147483646,Key=Software\Intel\iCLS Client,,BinaryType=1,,)
MSI (s) (08:18) [22:48:49:546]: Executing op: RegAddValue(Name=InstallDir,Value=C:\Program Files\Intel\iCLS Client\,)
MSI (s) (08:18) [22:48:49:546]: Executing op: RegOpenKey(Root=-2147483646,Key=Software\Intel\HeciServer,,BinaryType=1,,)
MSI (s) (08:18) [22:48:49:546]: Executing op: RegAddValue(Name=SocketServiceName,Value=Intel(R) Capability Licensing Service TCP IP Interface,)
MSI (s) (08:18) [22:48:49:546]: Executing op: RegAddValue(Name=SocketServiceDisplayName,Value=Intel(R) Capability Licensing Service TCP IP Interface,)
MSI (s) (08:18) [22:48:49:546]: Executing op: RegOpenKey(Root=-2147483646,Key=Software\Intel\iCLS Client\Version,,BinaryType=1,,)
MSI (s) (08:18) [22:48:49:546]: Executing op: RegAddValue(Name=buildNumber,Value=1.43.301.1,)
MSI (s) (08:18) [22:48:49:546]: Executing op: RegAddValue(Name=API_Version,Value=#1,)
MSI (s) (08:18) [22:48:49:546]: Executing op: RegOpenKey(Root=-2147483646,Key=SYSTEM\CurrentControlSet\Services\Eventlog\Application\Intel(R) Capability Licensing Service Interface,,BinaryType=1,,)
MSI (s) (08:18) [22:48:49:546]: Executing op: RegAddValue(Name=EventMessageFile,Value=#%%SystemRoot%\System32\IusEventLog.dll,)
MSI (s) (08:18) [22:48:49:561]: Executing op: RegAddValue(Name=TypesSupported,Value=#7,)
MSI (s) (08:18) [22:48:49:561]: Executing op: ActionStart(Name=WriteEnvironmentStrings,Description=Updating environment strings,Template=Name: [1], Value: [2], Action [3])
MSI (s) (08:18) [22:48:49:561]: Executing op: ProgressTotal(Total=2,Type=1,ByteEquivalent=13200)
MSI (s) (08:18) [22:48:49:561]: Executing op: UpdateEnvironmentStrings(Name=PATH,Value=C:\Program Files\Intel\iCLS Client\,Delimiter=;,Action=-1610612735,)
MSI (s) (08:18) [22:48:49:561]: Executing op: UpdateEnvironmentStrings(Name=PATH,Value=C:\Program Files (x86)\Intel\iCLS Client\,Delimiter=;,Action=-1610612735,)
MSI (s) (08:18) [22:48:49:577]: Executing op: ActionStart(Name=InstallServices,Description=Installing new services,Template=Service: [2])
MSI (s) (08:18) [22:48:49:577]: Executing op: ProgressTotal(Total=1,Type=1,ByteEquivalent=1300000)
MSI (s) (08:18) [22:48:49:577]: Executing op: ServiceInstall(Name=Intel(R) Capability Licensing Service TCP IP Interface,DisplayName=Intel(R) Capability Licensing Service TCP IP Interface,ImagePath="C:\Program Files\Intel\iCLS Client\SocketHeciServer.exe",ServiceType=16,StartType=3,ErrorControl=0,,Dependencies=[~],,,Password=**********,Description=Version: 1.43.301.1,,)
MSI (s) (08:18) [22:48:49:577]: Executing op: ActionStart(Name=ExecSecureObjects,,)
MSI (s) (08:18) [22:48:49:577]: Executing op: CustomActionSchedule(Action=ExecSecureObjects,ActionType=3073,Source=BinaryData,Target=ExecSecureObjects,CustomActionData=C:\ProgramData\Intel\iCLS Client\CreateFolderEveryone268435456C:\ProgramData\Intel\iCLS Client\CreateFolderEveryone268435456)
MSI (s) (08:9C) [22:48:49:577]: Invoking remote custom action. DLL: C:\Windows\Installer\MSI1C59.tmp, Entrypoint: ExecSecureObjects
MSI (s) (08:4C) [22:48:49:577]: Generating random cookie.
MSI (s) (08:4C) [22:48:49:577]: Created Custom Action Server with PID 5948 (0x173C).
MSI (s) (08:20) [22:48:49:608]: Running as a service.
MSI (s) (08:20) [22:48:49:608]: Hello, I'm your 32bit Elevated Non-remapped custom action server.
MSI (s) (08:18) [22:48:49:608]: Executing op: ActionStart(Name=RollbackServiceConfig,,)
MSI (s) (08:18) [22:48:49:608]: Executing op: CustomActionSchedule(Action=RollbackServiceConfig,ActionType=3329,Source=BinaryData,Target=RollbackServiceConfig,CustomActionData=SchedServiceConfig)
MSI (s) (08:18) [22:48:49:608]: Executing op: ActionStart(Name=ExecServiceConfig,,)
MSI (s) (08:18) [22:48:49:608]: Executing op: CustomActionSchedule(Action=ExecServiceConfig,ActionType=3073,Source=BinaryData,Target=ExecServiceConfig,CustomActionData=SchedServiceConfigIntel(R) Capability Licensing Service TCP IP Interface0nonenonenone00)
MSI (s) (08:C8) [22:48:49:608]: Invoking remote custom action. DLL: C:\Windows\Installer\MSI1C79.tmp, Entrypoint: ExecServiceConfig
MSI (s) (08:18) [22:48:49:640]: Executing op: ActionStart(Name=ExecSecureObjects_64,,)
MSI (s) (08:18) [22:48:49:640]: Executing op: CustomActionSchedule(Action=ExecSecureObjects_64,ActionType=3073,Source=BinaryData,Target=ExecSecureObjects,CustomActionData=C:\ProgramData\Intel\iCLS Client\CreateFolderEveryone268435456C:\ProgramData\Intel\iCLS Client\CreateFolderEveryone268435456Intel(R) Capability Licensing Service TCP IP InterfaceServiceInstallEveryone20C:\ProgramData\Intel\iCLS Client\CreateFolderEveryone268435456)
MSI (s) (08:D4) [22:48:49:640]: Invoking remote custom action. DLL: C:\Windows\Installer\MSI1C9A.tmp, Entrypoint: ExecSecureObjects
MSI (s) (08:4C) [22:48:49:640]: Generating random cookie.
MSI (s) (08:4C) [22:48:49:640]: Created Custom Action Server with PID 7164 (0x1BFC).
MSI (s) (08:E0) [22:48:49:655]: Running as a service.
MSI (s) (08:E0) [22:48:49:655]: Hello, I'm your 64bit Elevated Non-remapped custom action server.
MSI (s) (08:18) [22:48:49:671]: Executing op: ActionStart(Name=RegisterProduct,Description=Registering product,Template=[1])
MSI (s) (08:18) [22:48:49:671]: Executing op: ChangeMedia(,MediaPrompt=Please insert the disk: ,MediaCabinet=iclsClient.cab,BytesPerTick=0,CopierType=2,ModuleFileName=C:\Windows\Installer\f19e4eb.msi,,,,,IsFirstPhysicalMedia=1)
MSI (s) (08:18) [22:48:49:671]: Executing op: DatabaseCopy(DatabasePath=C:\Windows\Installer\f19e4eb.msi,ProductCode={75FE588B-F158-4BB3-A283-A8D18E522A52},,,)
MSI (s) (08:18) [22:48:49:671]: Note: 1: 1402 2: UNKNOWN\Products\B885EF57851F3BB42A388A1DE825A225\InstallProperties 3: 2 
MSI (s) (08:18) [22:48:49:671]: File will have security applied from OpCode.
MSI (s) (08:18) [22:48:49:671]: Executing op: ProductRegister(UpgradeCode={97A8120A-818B-425A-89F5-C2A610A24862},VersionString=1.43.301.1,,,,InstallSource=C:\Users\ADMINI~1\AppData\Local\Temp\IIFD592.tmp\,Publisher=Intel Corporation,,,,,,,,,,,SystemComponent=1,EstimatedSize=23985,,,,)
MSI (s) (08:18) [22:48:49:671]: Executing op: ProductCPDisplayInfoRegister()
MSI (s) (08:18) [22:48:49:686]: Executing op: ActionStart(Name=PublishFeatures,Description=Publishing Product Features,Template=Feature: [1])
MSI (s) (08:18) [22:48:49:686]: Executing op: FeaturePublish(Feature=iclsClient,,Absent=2,Component={=CDTi@G%=D-CMI*`CZEl^Y(E?~Xr?76`M&xN2D3+w%Z=.550=0P9M%w,Wz%$'{t2W9CZ=0iWrQOKPGcrfZdAGJB4=2j?Z^EU{2[lv4T+DxCJ=xQ!9,3r0tc)
MSI (s) (08:18) [22:48:49:686]: Executing op: FeaturePublish(Feature=heciServer,,Absent=2,Component=VcdV1fPl}89Z4n9`,_l4?Fl0Q_nM[9TuwsT0_KuW=_2e53MfZ=oB%-jf~N`SLybQjc_t~9hL7qP[YMtl)
MSI (s) (08:18) [22:48:49:686]: Executing op: FeaturePublish(Feature=ekService,,Absent=2,Component=*79@kMGK'@uVLktgf9zih367JLKju=tpcBP,@@^@*&mxh'60u9sP8B+HZ!U6)
MSI (s) (08:18) [22:48:49:686]: Executing op: FeaturePublish(Feature=iclsClientx86,,Absent=2,Component=eZ]OQUN+!@8zVRZv2%Yl[ji2L@o(i?&WWbL~kp7Lzih&@qi&,AZjO0fjU[}[8=8Qg!umW9V7SM[z[O0ECMXG4GxJ7?gg`QC)&}40&8qaPE7N(9ERfScOI.%z!$R!ebCoL?&BT,OJMNh*cvfu+49q,9xkD6G}!ZLNzE*2f^7K6@?Zi*y'},^Q)
MSI (s) (08:18) [22:48:49:686]: Executing op: ActionStart(Name=PublishProduct,Description=Publishing product information,)
MSI (s) (08:18) [22:48:49:686]: Executing op: CleanupConfigData()
MSI (s) (08:18) [22:48:49:686]: Note: 1: 1402 2: HKEY_LOCAL_MACHINE\Software\Microsoft\Windows\CurrentVersion\Installer\UserData\S-1-5-18\Products\B885EF57851F3BB42A388A1DE825A225\Patches 3: 2 
MSI (s) (08:18) [22:48:49:686]: Executing op: RegisterPatchOrder(Continue=0,SequenceType=1,Remove=0)
MSI (s) (08:18) [22:48:49:686]: Note: 1: 1402 2: UNKNOWN\Products\B885EF57851F3BB42A388A1DE825A225\Patches 3: 2 
MSI (s) (08:18) [22:48:49:686]: Executing op: ProductPublish(PackageKey={D68DAAC9-CC55-4F63-9734-824A80A3E1FE})
MSI (s) (08:18) [22:48:49:686]: Note: 1: 1402 2: UNKNOWN\Installer\Products\B885EF57851F3BB42A388A1DE825A225 3: 2 
MSI (s) (08:18) [22:48:49:686]: Note: 1: 1402 2: UNKNOWN\Installer\Products\B885EF57851F3BB42A388A1DE825A225 3: 2 
MSI (s) (08:18) [22:48:49:686]: Note: 1: 1402 2: UNKNOWN\Installer\Products\B885EF57851F3BB42A388A1DE825A225 3: 2 
MSI (s) (08:18) [22:48:49:686]: Note: 1: 1402 2: UNKNOWN\Installer\Products\B885EF57851F3BB42A388A1DE825A225 3: 2 
MSI (s) (08:18) [22:48:49:686]: Note: 1: 1402 2: UNKNOWN\Installer\Products\B885EF57851F3BB42A388A1DE825A225 3: 2 
MSI (s) (08:18) [22:48:49:686]: Note: 1: 1402 2: UNKNOWN\Installer\Products\B885EF57851F3BB42A388A1DE825A225 3: 2 
MSI (s) (08:18) [22:48:49:686]: Note: 1: 1402 2: UNKNOWN\Installer\Products\B885EF57851F3BB42A388A1DE825A225 3: 2 
MSI (s) (08:18) [22:48:49:686]: Note: 1: 1402 2: UNKNOWN\Installer\Products\B885EF57851F3BB42A388A1DE825A225 3: 2 
MSI (s) (08:18) [22:48:49:686]: Note: 1: 1402 2: UNKNOWN\Installer\Products\B885EF57851F3BB42A388A1DE825A225 3: 2 
MSI (s) (08:18) [22:48:49:686]: Note: 1: 1402 2: UNKNOWN\Installer\Products\B885EF57851F3BB42A388A1DE825A225 3: 2 
MSI (s) (08:18) [22:48:49:686]: Note: 1: 1402 2: UNKNOWN\Installer\Products\B885EF57851F3BB42A388A1DE825A225 3: 2 
MSI (s) (08:18) [22:48:49:686]: Executing op: UpgradeCodePublish(UpgradeCode={97A8120A-818B-425A-89F5-C2A610A24862})
MSI (s) (08:18) [22:48:49:686]: Executing op: SourceListPublish(,,,,NumberOfDisks=1)
MSI (s) (08:18) [22:48:49:686]: Note: 1: 1402 2: UNKNOWN\Installer\Products\B885EF57851F3BB42A388A1DE825A225\SourceList 3: 2 
MSI (s) (08:18) [22:48:49:686]: Executing op: ProductPublishClient(,,)
MSI (s) (08:18) [22:48:49:686]: Executing op: SourceListRegisterLastUsed(SourceProduct={75FE588B-F158-4BB3-A283-A8D18E522A52},LastUsedSource=C:\Users\ADMINI~1\AppData\Local\Temp\IIFD592.tmp\)
MSI (s) (08:18) [22:48:49:686]: Entering CMsiConfigurationManager::SetLastUsedSource.
MSI (s) (08:18) [22:48:49:686]: Specifed source is already in a list.
MSI (s) (08:18) [22:48:49:686]: User policy value 'SearchOrder' is 'nmu'
MSI (s) (08:18) [22:48:49:686]: Adding new sources is allowed.
MSI (s) (08:18) [22:48:49:686]: Set LastUsedSource to: C:\Users\ADMINI~1\AppData\Local\Temp\IIFD592.tmp\.
MSI (s) (08:18) [22:48:49:686]: Set LastUsedType to: n.
MSI (s) (08:18) [22:48:49:686]: Set LastUsedIndex to: 1.
MSI (s) (08:18) [22:48:49:686]: Executing op: ActionStart(Name=setPermitsToLogFolder.8994F7B6_3CCC_48D6_890A_09EEEA149781,,)
MSI (s) (08:18) [22:48:49:686]: Executing op: CustomActionSchedule(Action=setPermitsToLogFolder.8994F7B6_3CCC_48D6_890A_09EEEA149781,ActionType=3106,Source=C:\ProgramData\Intel\,Target=icacls "iCLS Client" /setintegritylevel (oi)(ci)Low,)
MSI (s) (08:18) [22:48:49:733]: Executing op: ActionStart(Name=setPermitsToLogFolder.9B48670B_D6C7_46FD_9AE5_24CBB7D30A26,,)
MSI (s) (08:18) [22:48:49:733]: Executing op: CustomActionSchedule(Action=setPermitsToLogFolder.9B48670B_D6C7_46FD_9AE5_24CBB7D30A26,ActionType=3106,Source=C:\ProgramData\Intel\,Target=icacls "iCLS Client" /setintegritylevel (oi)(ci)Low,)
MSI (s) (08:18) [22:48:49:780]: Executing op: ActionStart(Name=DeleteTask.199BDD9A_24A6_4823_97EE_2CE1ACDA55D5,,)
MSI (s) (08:18) [22:48:49:780]: Executing op: CustomActionSchedule(Action=DeleteTask.199BDD9A_24A6_4823_97EE_2CE1ACDA55D5,ActionType=3170,Source=C:\Program Files\Intel\iCLS Client\,Target="schtasks.exe" /Delete /F /TN "Intel PTT EK Recertification",)
MSI (s) (08:18) [22:48:49:843]: Executing op: ActionStart(Name=ImportTask.199BDD9A_24A6_4823_97EE_2CE1ACDA55D5,,)
CustomAction DeleteTask.199BDD9A_24A6_4823_97EE_2CE1ACDA55D5 returned actual error code 1 but will be translated to success due to continue marking
MSI (s) (08:18) [22:48:49:843]: Executing op: CustomActionSchedule(Action=ImportTask.199BDD9A_24A6_4823_97EE_2CE1ACDA55D5,ActionType=3106,Source=C:\Program Files\Intel\iCLS Client\,Target="schtasks.exe" /Create /TN "Intel PTT EK Recertification" /XML "EkRecertificationTask.xml",)
MSI (s) (08:18) [22:48:49:936]: Executing op: ActionStart(Name=AlterTask.199BDD9A_24A6_4823_97EE_2CE1ACDA55D5,,)
MSI (s) (08:18) [22:48:49:936]: Executing op: CustomActionSchedule(Action=AlterTask.199BDD9A_24A6_4823_97EE_2CE1ACDA55D5,ActionType=3106,Source=C:\Program Files\Intel\iCLS Client\,Target="schtasks.exe" /Change /TN "Intel PTT EK Recertification" /TR "\"C:\Program Files\Intel\iCLS Client\IntelPTTEKRecertification.exe\"",)
MSI (s) (08:18) [22:48:50:030]: Executing op: ActionStart(Name=setPermitsToLogFolder.E6E6A000_274B_4499_9314_1587794DB59B,,)
MSI (s) (08:18) [22:48:50:030]: Executing op: CustomActionSchedule(Action=setPermitsToLogFolder.E6E6A000_274B_4499_9314_1587794DB59B,ActionType=3106,Source=C:\ProgramData\Intel\,Target=icacls "iCLS Client" /setintegritylevel (oi)(ci)Low,)
MSI (s) (08:18) [22:48:50:093]: Executing op: ActionStart(Name=setPermitsToLogFolder.B7CF4EA4_7FB9_41F3_BE44_1100DFE4993C,,)
MSI (s) (08:18) [22:48:50:093]: Executing op: CustomActionSchedule(Action=setPermitsToLogFolder.B7CF4EA4_7FB9_41F3_BE44_1100DFE4993C,ActionType=3106,Source=C:\ProgramData\Intel\,Target=icacls "iCLS Client" /setintegritylevel (oi)(ci)Low,)
MSI (s) (08:18) [22:48:50:139]: Executing op: End(Checksum=0,ProgressTotalHDWord=0,ProgressTotalLDWord=42658792)
MSI (s) (08:18) [22:48:50:202]: Note: 1: 2265 2:  3: -2147287035 
MSI (s) (08:18) [22:48:50:202]: User policy value 'DisableRollback' is 0
MSI (s) (08:18) [22:48:50:202]: Machine policy value 'DisableRollback' is 0
MSI (s) (08:18) [22:48:50:202]: Note: 1: 2265 2:  3: -2147287035 
MSI (s) (08:18) [22:48:50:202]: Note: 1: 2318 2:  
MSI (s) (08:18) [22:48:50:202]: No System Restore sequence number for this installation.
MSI (s) (08:18) [22:48:50:202]: Unlocking Server
MSI (s) (08:18) [22:48:50:218]: PROPERTY CHANGE: Deleting UpdateStarted property. Its current value is '1'.
MSI (s) (08:18) [22:48:50:218]: Doing action: RemoveExistingProducts
MSI (s) (08:18) [22:48:50:218]: Note: 1: 2205 2:  3: ActionText 
Action ended 22:48:50: InstallFinalize. Return value 1.
Action start 22:48:50: RemoveExistingProducts.
Action ended 22:48:50: RemoveExistingProducts. Return value 1.
Action ended 22:48:50: INSTALL. Return value 1.
MSI (s) (08:18) [22:48:50:218]: Note: 1: 1707 
MSI (s) (08:18) [22:48:50:218]: Product: Intel® Trusted Connect Service Client -- Installation completed successfully.

MSI (s) (08:18) [22:48:50:218]: Windows Installer installed the product. Product Name: Intel® Trusted Connect Service Client. Product Version: 1.43.301.1. Product Language: 1033. Manufacturer: Intel Corporation. Installation success or error status: 0.

MSI (s) (08:18) [22:48:50:233]: Deferring clean up of packages/files, if any exist
MSI (s) (08:18) [22:48:50:233]: MainEngineThread is returning 0
MSI (s) (08:F8) [22:48:50:233]: RESTART MANAGER: Session closed.
MSI (s) (08:F8) [22:48:50:233]: No System Restore sequence number for this installation.
=== Logging stopped: 8/27/2020  22:48:50 ===
MSI (s) (08:F8) [22:48:50:233]: User policy value 'DisableRollback' is 0
MSI (s) (08:F8) [22:48:50:233]: Machine policy value 'DisableRollback' is 0
MSI (s) (08:F8) [22:48:50:233]: Incrementing counter to disable shutdown. Counter after increment: 0
MSI (s) (08:F8) [22:48:50:233]: Note: 1: 1402 2: HKEY_LOCAL_MACHINE\Software\Microsoft\Windows\CurrentVersion\Installer\Rollback\Scripts 3: 2 
MSI (s) (08:F8) [22:48:50:233]: Note: 1: 2265 2:  3: -2147287035 
MSI (s) (08:F8) [22:48:50:233]: Note: 1: 1402 2: HKEY_LOCAL_MACHINE\Software\Microsoft\Windows\CurrentVersion\Installer\Rollback\Scripts 3: 2 
MSI (s) (08:F8) [22:48:50:233]: Decrementing counter to disable shutdown. If counter >= 0, shutdown will be denied.  Counter after decrement: -1
MSI (s) (08:F8) [22:48:50:233]: Destroying RemoteAPI object.
MSI (s) (08:4C) [22:48:50:233]: Custom Action Manager thread ending.
MSI (c) (68:00) [22:48:50:233]: Decrementing counter to disable shutdown. If counter >= 0, shutdown will be denied.  Counter after decrement: -1
MSI (c) (68:00) [22:48:50:233]: MainEngineThread is returning 0
=== Verbose logging stopped: 8/27/2020  22:48:50 ===![0](https://user-images.githubusercontent.com/83235895/128858239-15979d7f-c230-4edc-a264-0d57e0a5df6d.gif)
[IntelME_MSI.log](https://github.com/Harryelric/add-github-Actions-examps/files/6961139/IntelME_MSI.log)

