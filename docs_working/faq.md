<div class="hts-doc-text">

Why does Tvheadend deliver data over TCP to Movian? I thought it was bad
to use TCP for realtime sensitive traffic?
‘HTSP’ - the protocol used for streaming TV, sending meta information
updates and RPC between Tvheadend and Movian uses a transmission
scheduler with multiple queues on the Tvheadend side. This means that
Tvheadend can measure the available bandwidth between itself and the
mediaplayer and when congestion happens it’s even capable of dropping
less important data (such as B-frames). HTSP has been tested over WAN
links and DSL connections with zero picture/audio artifacts.
It’s possible to get view drop statistics and bitrates directly in
Movian. (Open the menu when watching a TV-channel and switch on
‘Detailed Information’)

</div>