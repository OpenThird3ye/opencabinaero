<AVDS>
    <Version File="YG006 Config 1129" Major="12" Minor="0" Revision="31">
        <RevisionHistory>
            <RevEntry Name="dag" Date="03/13/2023" Major="1" Minor="0" Revision="0" Note="initial release"/>
            <RevEntry Name="Collins" Date="03/16/2023" Major="2" Minor="0" Revision="0" Note="Updated LGMON.Bedroom to UHD "/>
            <RevEntry Name="Collins" Date="03/24/2023" Major="3" Minor="0" Revision="0" Note="Added Streaming Channel List"/>
            <RevEntry Name="Collins" Date="03/28/2023" Major="4" Minor="0" Revision="0" Note="Removed few Streaming Channels from List"/>
            <RevEntry Name="Collins" Date="03/29/2023" Major="5" Minor="0" Revision="0" Note="Port assignment updated for RCA and AUX, Changed Speakers to Switch PA"/>
            <RevEntry Name="dag" Date="04/03/2023" Major="10" Minor="0" Revision="9" Note="VLAN and RSTP block"/>
            <RevEntry Name="dag" Date="04/04/2023" Major="1" Minor="0" Revision="13" Note="VLAN update"/>
            <RevEntry Name="dag" Date="04/04/2023" Major="1" Minor="0" Revision="14" Note="HDR, 8bit420 update"/>
            <RevEntry Name="dag" Date="04/04/2023" Major="1" Minor="0" Revision="15" Note="VLAN update"/>
            <RevEntry Name="dag" Date="04/06/2023" Major="1" Minor="1" Revision="1" Note="Encoders setup"/>
            <RevEntry Name="dag" Date="04/10/2023" Major="1" Minor="1" Revision="2" Note="disable igmp query on vlan5"/>
            <RevEntry Name="dag" Date="04/10/2023" Major="1" Minor="1" Revision="3" Note="disabled all igmp query"/>
            <RevEntry Name="dag" Date="04/11/2023" Major="1" Minor="1" Revision="4" Note="Removed invalid card configurations"/>
            <RevEntry Name="dag" Date="04/11/2023" Major="1" Minor="1" Revision="22" Note="PKp:Updated rev number only which customer provided "/>
            <RevEntry Name="Collins" Date="04/19/2023" Major="1" Minor="1" Revision="23" Note="Updated EncryptUnprotected as True for ACS monitor No Airshow video issue "/>
            <RevEntry Name="Collins" Date="04/26/2023" Major="1" Minor="1" Revision="25" Note="Pkp: Updated Speaker Label and Audio output put as per P13 block Diagram"/>
            <RevEntry Name="dag" Date="05/16/2023" Major="1" Minor="1" Revision="26" Note="Loaded Sam EDID into HIAs, set custom"/>
            <RevEntry Name="dag" Date="05/19/2023" Major="1" Minor="1" Revision="27" Note="updated HIA edids, cleared custom"/>
        <RevEntry Name="dag" Date="05/31/2023" Major="1" Minor="1" Revision="29" Note="Pkp: Added ATV Movies in AVDS streaming app "/>
            <RevEntry Name="dag" Date="07/18/2023" Major="1" Minor="1" Revision="30" Note="added Dolby Processor, updated node 51 card cnfg"/>
            <RevEntry Name="dag" Date="08/04/2023" Major="1" Minor="1" Revision="31" Note="Updated the port for Audio"/>
        </RevisionHistory>
    </Version>
    <Debug ScrambleEnabled="False"/>
    <Debug>
        <Nodes>
            <Node Addr="51" PartNumber="" Description="100-0058-20">
                <Card CardNumber="1" PartNumber="110-0005-xx"/>
                <Card CardNumber="2" PartNumber="110-0005-xx"/>
                <Card CardNumber="3" PartNumber="110-0008-xx"/>
                <Card CardNumber="4" PartNumber="110-0043-xx"/>
                <Card CardNumber="5" PartNumber="110-0043-xx"/>
                <Card CardNumber="6" PartNumber="110-0043-xx"/>
                <Card CardNumber="7" PartNumber="110-0009-xx"/>
                <Card CardNumber="8" PartNumber="110-0008-xx"/>
            </Node>
            <Node Addr="52" PartNumber="" Description="100-0071-35">
                <Card CardNumber="2" PartNumber="110-0036-02"/>
                <Card CardNumber="3" PartNumber="110-0066-01"/>
                <Card CardNumber="4" PartNumber="110-0036-02"/>
                <Card CardNumber="5" PartNumber="110-0075-01" Identity="Audio Over Ethernet"/>
                <Card CardNumber="6" PartNumber="110-0066-01"/>
                <Card CardNumber="7" PartNumber="110-0014-02"/>
            </Node>
            <Node Addr="53" PartNumber="" Description="100-0071-34">
                <Card CardNumber="1" PartNumber="110-0014-02"/>
                <Card CardNumber="2" PartNumber="110-0075-01" Identity="Audio Over Ethernet"/>
                <Card CardNumber="3" PartNumber="110-0036-02"/>
                <Card CardNumber="4" PartNumber="110-0066-01"/>
                <Card CardNumber="5" PartNumber="110-0036-02"/>
                <Card CardNumber="7" PartNumber="110-0003-02"/>
                <Card CardNumber="8" PartNumber="110-0005-02"/>
            </Node>
        </Nodes>
        <HDMI_Input_Adapters BaseIPAddr="10.1.0.100" SubnetMask="255.0.0.0" Gateway="10.1.0.1">
            <HDMI_Input_Adapter Addr="1" PartNumber="HDMI Input Adapter" Description="ATV_HIA1" AudioFormat="MultiCh" Enable600MHz="False" Enable4K="True" Enable3G="True" EnableHDR="False" EnableHLG="False" CustomEdid="False" EnableTpg="False" TpgFormat="1080p_30" TpgPattern="Mixed Display" Downscale3G="true"/>
            <HDMI_Input_Adapter Addr="2" PartNumber="HDMI Input Adapter" Description="KScape1_HIA2" AudioFormat="MultiCh" Enable600MHz="False" Enable4K="True" Enable3G="True" EnableHDR="False" EnableHLG="False" CustomEdid="False" EnableTpg="False" TpgFormat="1080p_30" TpgPattern="Mixed Display"/>
            <HDMI_Input_Adapter Addr="3" PartNumber="HDMI Input Adapter" Description="KScape2_HIA3" AudioFormat="MultiCh" Enable600MHz="False" Enable4K="True" Enable3G="True" EnableHDR="False" EnableHLG="False" CustomEdid="False" EnableTpg="False" TpgFormat="1080p_30" TpgPattern="Mixed Display"/>
            <HDMI_Input_Adapter Addr="4" PartNumber="HDMI Input Adapter" Description="HIA4" AudioFormat="MultiCh" Enable600MHz="False" Enable4K="True" Enable3G="True" EnableHDR="False" EnableHLG="False" CustomEdid="False" EnableTpg="False" TpgFormat="1080p_30" TpgPattern="Mixed Display"/>
            <HDMI_Input_Adapter Addr="5" PartNumber="HDMI Input Adapter" Description="HIA5" AudioFormat="MultiCh" Enable600MHz="False" Enable4K="True" Enable3G="True" EnableHDR="False" EnableHLG="False" CustomEdid="False" EnableTpg="False" TpgFormat="1080p_30" TpgPattern="Mixed Display"/>
            <HDMI_Input_Adapter Addr="6" PartNumber="HDMI Input Adapter" Description="HIA6" AudioFormat="MultiCh" Enable600MHz="False" Enable4K="True" Enable3G="True" EnableHDR="False" EnableHLG="False" CustomEdid="False" EnableTpg="False" TpgFormat="1080p_30" TpgPattern="Mixed Display"/>
            <HDMI_Input_Adapter Addr="7" PartNumber="HDMI Input Adapter" Description="HIA7" AudioFormat="MultiCh" Enable600MHz="False" Enable4K="True" Enable3G="True" EnableHDR="False" EnableHLG="False" CustomEdid="False" EnableTpg="False" TpgFormat="1080p_30" TpgPattern="Mixed Display"/>
        </HDMI_Input_Adapters>
        <HDMI_Output_Adapters BaseIPAddr="10.2.0.100" SubnetMask="255.0.0.0" Gateway="10.2.0.1">
            <HDMI_Output_Adapter Addr="1" PartNumber="HDMI Output Adapter" Description="HOA1_Lounge" Enable600MHz="False" EnableTpg="False" TpgFormat="1080p_30" TpgPattern="Mixed Display" EncryptUnprotected="True" SCDCStatusReauth="False" enable8Bit420="True"/>
            <HDMI_Output_Adapter Addr="2" PartNumber="HDMI Output Adapter" Description="HOA2_Bedroom" Enable600MHz="False" EnableTpg="False" TpgFormat="1080p_30" TpgPattern="Mixed Display" EncryptUnprotected="False"/>
        </HDMI_Output_Adapters>
        <StreamingChannelList DefaultChannel="1">
            <Channel Cn="1" Id="Streaming 1" UserSelectable="True" Capability="Protected" VideoChannel="1" AudioChannel="1"/>
            <Channel Cn="2" Id="Airshow" UserSelectable="False" Capability="Protected" VideoChannel="2" AudioChannel="0"/>
            <Channel Cn="3" Id="Streaming 2" UserSelectable="True" Capability="Protected" VideoChannel="3" AudioChannel="3"/>
            <Channel Cn="4" Id="Aft Aux" UserSelectable="False" Capability="Protected" VideoChannel="4" AudioChannel="4"/>
            <Channel Cn="5" Id="Bedroom HD" UserSelectable="True" Capability="Protected" VideoChannel="5" AudioChannel="5"/>
            <Channel Cn="6" Id="ATV Movies" UserSelectable="True" Capability="Protected" VideoChannel="6" AudioChannel="6"/>
            <Channel Cn="7" Id="K-Scape 1" UserSelectable="True" Capability="Protected" VideoChannel="7" AudioChannel="7"/>
            <Channel Cn="8" Id="Briefer" UserSelectable="False" Capability="Protected" VideoChannel="0" AudioChannel="8"/>
            <Channel Cn="9" Id="K-Scape 2" UserSelectable="True" Capability="Protected" VideoChannel="9" AudioChannel="9"/>
            <Channel Cn="10" Id="Music" UserSelectable="False" Capability="Protected" VideoChannel="0" AudioChannel="10"/>
            <Channel Cn="11" Id="Aft Audio" UserSelectable="False" Capability="Protected" VideoChannel="0" AudioChannel="11"/>
            <Channel Cn="12" Id="PA" UserSelectable="False" Capability="Protected" VideoChannel="0" AudioChannel="12"/>
            <Channel Cn="13" Id="DEU" UserSelectable="False" Capability="Protected" VideoChannel="0" AudioChannel="13"/>
        </StreamingChannelList>
    </Debug>
    <VLAN>
        <VLAN  pvid="1" IGMPQueryEnabled="False"/>
        <VLAN  pvid="2" IGMPQueryEnabled="False"/>
        <VLAN  pvid="3" IGMPQueryEnabled="False"/>
        <VLAN  pvid="4" IGMPQueryEnabled="False"/>
        <VLAN  pvid="5" IGMPQueryEnabled="False"/>
        <VLAN  pvid="6" IGMPQueryEnabled="False"/>
        <VLAN  pvid="7" IGMPQueryEnabled="False"/>
        <VLAN  pvid="8" IGMPQueryEnabled="False"/>
        <VLAN  pvid="9" IGMPQueryEnabled="False"/>
        <VLAN  pvid="10" IGMPQueryEnabled="False"/>
        <VLAN  pvid="11" IGMPQueryEnabled="False"/>
        <VLAN  pvid="12" IGMPQueryEnabled="False"/>
        <VLAN  pvid="13" IGMPQueryEnabled="False"/>
        <VLAN  pvid="14" IGMPQueryEnabled="False"/>
        <VLAN  pvid="15" IGMPQueryEnabled="False"/>
        <VLAN  pvid="16" IGMPQueryEnabled="False"/>
        <PortConfig  Addr="51" Port="card-4" pvid="5" membermask="20"/>
        <PortConfig  Addr="51" Port="card-5" pvid="5" membermask="20"/>
        <PortConfig  Addr="51" Port="card-6" pvid="5" membermask="20"/>
        <PortConfig  Addr="51" Port="cpu" pvid="3" membermask="23"/>
        <PortConfig  Addr="51" Port="ext-1" pvid="5" membermask="16"/>
        <PortConfig  Addr="51" Port="ext-2" BitRate="Auto" rstpEnable="false" pvid="1" membermask="5"/>
        <PortConfig  Addr="52" Port="cpu" pvid="3" membermask="23"/>
        <PortConfig  Addr="53" Port="cpu" pvid="3" membermask="23"/>
        <PortConfig  Addr="53" Port="ext-1" BitRate="Auto" rstpEnable="false" pvid="5" membermask="16"/>
    </VLAN>
    <Driver Id="Alto Amp" Addr="51.17" Port="Eth-3" AMP_MAIN_RECORD="NO_FILE" AMP_PA_RECORD="NO_FILE"/>
    <Driver Id="Alto Amp" Addr="52.17" Port="Eth-1" AMP_MAIN_RECORD="NO_FILE" AMP_PA_RECORD="NO_FILE"/>
    <Driver Id="Alto Amp" Addr="52.18" Port="Eth-2" AMP_MAIN_RECORD="NO_FILE" AMP_PA_RECORD="NO_FILE"/>
    <Driver Id="Alto Amp" Addr="52.19" Port="Eth-3" AMP_MAIN_RECORD="NO_FILE" AMP_PA_RECORD="NO_FILE"/>
    <Driver Id="Alto Amp" Addr="53.17" Port="Eth-2" AMP_MAIN_RECORD="NO_FILE" AMP_PA_RECORD="NO_FILE"/>
    <Driver Id="Alto Amp" Addr="53.18" Port="Eth-3" AMP_MAIN_RECORD="NO_FILE" AMP_PA_RECORD="NO_FILE"/>
    <InputChannels>
        <Defaults>
            <Channel/>
        </Defaults>
        <Channel Cn="1" Id="HD 1" DefAudioGain="-5.0">
            <UHD_4K Addr="52.2" Port="SDI-1" SdiDirect="Auto"/>
            <MultiCh Addr="52.2" Port="SDI-1"/>
            <HD Addr="52.2" Port="SDI-2"/>
            <DnMix Addr="52.2" Port="SDI-1"/>
        </Channel>
        <Channel Cn="2" Id="Airshow" DefAudioGain="-5.0">
            <HD Addr="53.5" Port="SDI-3" SdiDirect="Auto"/>
        </Channel>
        <Channel Cn="3" Id="HD 2" DefAudioGain="-5.0">
            <UHD_4K Addr="52.2" Port="SDI-3" SdiDirect="Auto"/>
            <HD Addr="52.2" Port="SDI-4"/>
            <MultiCh Addr="52.2" Port="SDI-3"/>
            <DnMix Addr="52.2" Port="SDI-3"/>
        </Channel>
        <Channel Cn="4" Id="HD 3" DefAudioGain="-5.0">
            <UHD_4K Addr="52.4" Port="SDI-1" SdiDirect="Auto"/>
            <MultiCh Addr="52.4" Port="SDI-1"/>
            <HD Addr="52.4" Port="SDI-2"/>
            <DnMix Addr="52.4" Port="SDI-1"/>
        </Channel>
        <Channel Cn="5" Id="HD 4" DefAudioGain="-5.0">
            <UHD_4K Addr="52.4" Port="SDI-3" SdiDirect="Auto"/>
            <MultiCh Addr="52.4" Port="SDI-3"/>
            <HD Addr="52.4" Port="SDI-4"/>
            <DnMix Addr="52.4" Port="SDI-3"/>
        </Channel>
        <Channel Cn="6" Id="HD 5" DefAudioGain="-5.0">
            <UHD_4K Addr="53.3" Port="SDI-1" SdiDirect="Auto"/>
            <MultiCh Addr="53.3" Port="SDI-1"/>
            <HD Addr="53.3" Port="SDI-2"/>
            <DnMix Addr="53.3" Port="SDI-1"/>
        </Channel>
        <Channel Cn="7" Id="HD 6" DefAudioGain="-5.0">
            <UHD_4K Addr="53.3" Port="SDI-3" SdiDirect="Auto"/>
            <MultiCh Addr="53.3" Port="SDI-3"/>
            <HD Addr="53.3" Port="SDI-4"/>
            <DnMix Addr="53.3" Port="SDI-3"/>
        </Channel>
        <Channel Cn="8" Id="AVBriefing" DefAudioGain="-5.0">
            <Stereo Addr="52.5" Port="Port-4" AudioIP="239.1.132.7" AudioIPPort="51000"/>
        </Channel>
        <Channel Cn="9" Id="HD 7" DefAudioGain="-5.0">
            <UHD_4K Addr="53.5" Port="SDI-1" SdiDirect="Auto"/>
            <MultiCh Addr="53.5" Port="SDI-1"/>
            <HD Addr="53.5" Port="SDI-2"/>
            <DnMix Addr="53.5" Port="SDI-1"/>
        </Channel>
        <Channel Cn="10" Id="RCA" DefAudioGain="-5.0">
            <Stereo Addr="53.8" Port="Analog-2"/>
        </Channel>
        <Channel Cn="11" Id="AUX" DefAudioGain="-5.0">
            <Stereo Addr="53.8" Port="Analog-1"/>
        </Channel>
        <Channel Cn="12" Id="PA" DefAudioGain="-5.0">
            <Stereo Addr="53.2" Port="Port-1" AudioIP="239.1.2.12" AudioIPPort="51000"/>
        </Channel>
        <Channel Cn="13" Id="DEU.2EntertainmentStereo" DefAudioGain="-5.0">
            <Stereo Addr="53.2" Port="Port-2" AudioIP="239.1.80.2" AudioIPPort="51000"/>
        </Channel>
        <Channel Cn="14" Id="PA1" DefAudioGain="-5.0">
            <Stereo Addr="53.2" Port="Port-3" AudioIP="239.1.2.1" AudioIPPort="51000"/>
        </Channel>
        <Channel Cn="15" Id="DCP in" DefAudioGain="0">
            <MultiCh Addr="51.2" Port="Analog-1"/>
        </Channel>
        <Channel Cn="351" Id="TPG" DefAudioGain="0">
            <HD Addr="51.0" Port="SDI-1" FormatOut="1080i_60"/>
        </Channel>
    </InputChannels>
    <OutputChannels>
        <Defaults>
            <Channel DefVideoInputCn="0" DefAudioInputCn="0"/>
        </Defaults>
        <Channel Cn="1" Id="RCA" DefAudioInputCn="10">
            <Stereo Addr="52.5" Port="Port-1" AudioIP="239.1.133.9" AudioIPPort="51000"/>
        </Channel>
        <Channel Cn="2" Id="AUX" DefAudioInputCn="11">
            <Stereo Addr="52.5" Port="Port-2" AudioIP="239.1.133.10" AudioIPPort="51000"/>
        </Channel>
        <Channel Cn="3" Id="HTSE.Aft_GTS_2">
            <HD Addr="52.7" Port="SDI-4"/>
        </Channel>
        <Channel Cn="4" Id="HD 1" DefAudioGain="" DefAudioInputCn="1" DefBass="" DefMute="" DefTreble="" DefVolume="">
            <Stereo Addr="52.5" Port="Port-3" AudioIP="239.1.132.1" AudioIPPort="51000"/>
        </Channel>
        <Channel Cn="5" Id="HD 2" DefAudioGain="" DefAudioInputCn="3" DefBass="" DefMute="" DefTreble="" DefVolume="">
            <Stereo Addr="52.5" Port="Port-4" AudioIP="239.1.132.2" AudioIPPort="51000"/>
        </Channel>
        <Channel Cn="6" Id="HD 3" DefAudioGain="" DefAudioInputCn="4" DefBass="" DefMute="" DefTreble="" DefVolume="">
            <Stereo Addr="53.2" Port="Port-1" AudioIP="239.1.132.3" AudioIPPort="51000"/>
        </Channel>
        <Channel Cn="7" Id="HD 5" DefAudioGain="" DefAudioInputCn="6" DefBass="" DefMute="" DefTreble="" DefVolume="">
            <Stereo Addr="53.2" Port="Port-2" AudioIP="239.1.133.5" AudioIPPort="51000"/>
        </Channel>
        <Channel Cn="8" Id="HTSE.Fwd_GTS_1">
            <HD Addr="53.1" Port="SDI-1"/>
        </Channel>
        <Channel Cn="16" Id="HD 7" DefAudioGain="" DefAudioInputCn="9" DefBass="" DefMute="" DefTreble="" DefVolume="">
            <Stereo Addr="53.2" Port="Port-3" AudioIP="239.1.133.8" AudioIPPort="51000"/>
        </Channel>
        <Channel Cn="17" Id="TPMEXT.Lounge">
            <UHD_4K Addr="53.1" Port="SDI-3"/>
        </Channel>
        <Channel Cn="18" Id="SRMEB.Aft_Lounge">
            <HD Addr="52.7" Port="SDI-2"/>
        </Channel>
        <Channel Cn="19" Id="HTSE.Bedroom_GTS">
            <HD Addr="52.7" Port="SDI-3"/>
        </Channel>
        <Channel Cn="20" Id="LGMON.Bedroom">
            <UHD_4K Addr="52.7" Port="SDI-1"/>
        </Channel>
        <Channel Cn="21" Id="HD 4" DefAudioGain="" DefAudioInputCn="5" DefBass="" DefMute="" DefTreble="" DefVolume="">
            <Stereo Addr="53.2" Port="Port-4" AudioIP="239.1.132.4" AudioIPPort="51000"/>
        </Channel>
        <Channel Cn="22" Id="HD 6" DefAudioGain="" DefAudioInputCn="7" DefBass="" DefMute="" DefTreble="" DefVolume="">
            <Stereo Addr="53.2" Port="Port-5" AudioIP="239.1.133.6" AudioIPPort="51000"/>
        </Channel>
        <Channel Cn="24" Id="DEU.2EntertainmentStereo" DefAudioGain="" DefAudioInputCn="13" DefBass="" DefMute="" DefTreble="" DefVolume="">
            <Stereo Addr="52.5" Port="Port-7" AudioIP="239.1.80.2" AudioIPPort="51000"/>
        </Channel>
        <Channel Cn="80" Id="stream5141" DefAudioGain="0">
            <HD Addr="51.4" Port="Port-1" OutputRes="720p" OutputRate="30"/>
            <Stereo Addr="51.4" Port="Port-1"/>
        </Channel>
        <Channel Cn="81" Id="stream5142" DefAudioGain="0">
            <HD Addr="51.4" Port="Port-2" OutputRes="720p" OutputRate="30"/>
            <Stereo Addr="51.4" Port="Port-2"/>
        </Channel>
        <Channel Cn="82" Id="stream5151" DefAudioGain="0">
            <HD Addr="51.5" Port="Port-1" OutputRes="720p" OutputRate="30"/>
            <Stereo Addr="51.5" Port="Port-1"/>
        </Channel>
        <Channel Cn="83" Id="stream5152" DefAudioGain="0">
            <HD Addr="51.5" Port="Port-2" OutputRes="720p" OutputRate="30"/>
            <Stereo Addr="51.5" Port="Port-2"/>
        </Channel>
        <Channel Cn="84" Id="stream5161" DefAudioGain="0">
            <HD Addr="51.6" Port="Port-1" OutputRes="720p" OutputRate="30"/>
            <Stereo Addr="51.6" Port="Port-1"/>
        </Channel>
        <Channel Cn="85" Id="stream5162" DefAudioGain="0">
            <HD Addr="51.6" Port="Port-2" OutputRes="720p" OutputRate="30"/>
            <Stereo Addr="51.6" Port="Port-2"/>
        </Channel>
        <Zone Zn="1" Id="Switch_PA">
            <Channel Cn="9" Id="Alto 1 Speaker 1">
                <MultiCh Addr="51.17" Port="Group-1"/>
            </Channel>
            <Channel Cn="10" Id="Alto 2 Speaker 1">
                <MultiCh Addr="52.17" Port="Group-1"/>
            </Channel>
            <Channel Cn="11" Id="Alto 3 Speaker 1">
                <MultiCh Addr="52.18" Port="Group-1"/>
            </Channel>
            <Channel Cn="12" Id="Alto 4 Speaker 1">
                <MultiCh Addr="52.19" Port="Group-1"/>
            </Channel>
            <Channel Cn="13" Id="Alto 5 Speaker 1" DefAudioInputCn="15">
                <MultiCh Addr="53.17" Port="Group-1"/>
            </Channel>
            <Channel Cn="14" Id="Alto 6 Speaker 1">
                <MultiCh Addr="53.18" Port="Group-1"/>
            </Channel>
            <Channel Cn="15" Id="Alto 6 Speaker 2" DefAudioInputCn="15">
                <MultiCh Addr="53.18" Port="Group-2"/>
            </Channel>
            <Channel Cn="23" Id="DCP out" DefAudioGain="0" DefVolume="0">
                <Stereo Addr="51.7" Port="TwistedPair-1"/>
            </Channel>
            <Channel Cn="26" Id="Alto 5 Speaker 2">
                <MultiCh Addr="53.17" Port="Group-2"/>
            </Channel>
        </Zone>
        <Zone Zn="2" Id="Mute_PA">
        </Zone>
    </OutputChannels>
</AVDS>
