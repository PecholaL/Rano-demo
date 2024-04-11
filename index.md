# Rano

## Abstract
<p align="justify">
</p>

## Architecture
<p align="justify">

</p>

<div style="text-align: center;">
<img src="assets/rano_frame.png" width = 1000 />
</div>
<p align="center">Figure.1 The Architecture of Rano</p>
<p>&nbsp;</p> 

## Audio Samples
<script>
function pauseOthers(ele) {
    $("audio").not(ele).each(function (index, audio) {audio.pause();});
}
</script>

<style>
.main-content table {
    display: inline-table;
}
table {
    table-layout:fixed;
    width: 100%;
    overflow: hidden;
}
#player{
    width: 100%;
}
</style>


<table>
    <CAPTION>Speaker-level speaker anonymization via Rano</CAPTION>
<tr>
<td>  </td>
<td> Original Speech </td>
<td> Anonymized Speech </td>
<td> Restored Speech </td>
</tr>

<tr>
<td rowspan="2"> I </td>
<td colspan="3"> "Please call Stellar." </td>
</tr>
<tr>
<td> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audio/orig225001.mp3" type="audio/mpeg"></audio> </td>
<td> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audio/p286_028.mp3" type="audio/mpeg"></audio> </td>
<td> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audio/res225001.mp3" type="audio/mpeg"></audio> </td>
</tr>

<tr>
<td rowspan="2"> II </td>
<td colspan="3"> "Ask her to bring these things with her from the store." </td>
</tr>
<tr>
<td> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audio/orig225002.mp3" type="audio/mpeg"></audio> </td>
<td> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audio/p286_028.mp3" type="audio/mpeg"></audio> </td>
<td> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audio/res225002.mp3" type="audio/mpeg"></audio> </td>
</tr>

<tr>
<td rowspan="2"> III </td>
<td colspan="3"> "We also need a small plastic snake and a big toy frog for the kids." </td>
</tr>
<tr>
<td> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audio/orig225004.mp3" type="audio/mpeg"></audio> </td>
<td> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audio/p286_028.mp3" type="audio/mpeg"></audio> </td>
<td> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audio/res225004.mp3" type="audio/mpeg"></audio> </td>
</tr>	

<tr>
<td rowspan="2"> VI </td>
<td colspan="3"> "They said she was stable." </td>
</tr>
<tr>
<td> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audio/orig246046.mp3" type="audio/mpeg"></audio> </td>
<td> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audio/p286_028.mp3" type="audio/mpeg"></audio> </td>
<td> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audio/res246046.mp3" type="audio/mpeg"></audio> </td>
</tr>

<tr>
<td rowspan="2"> V </td>
<td colspan="3"> "Is a drug dealer?" </td>
</tr>
<tr>
<td> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audio/orig246047.mp3" type="audio/mpeg"></audio> </td>
<td> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audio/p286_028.mp3" type="audio/mpeg"></audio> </td>
<td> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audio/res246047.mp3" type="audio/mpeg"></audio> </td>
</tr>

<tr>
<td rowspan="2"> VI </td>
<td colspan="3"> "The State would provide." </td>
</tr>
<tr>
<td> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audio/orig246049.mp3" type="audio/mpeg"></audio> </td>
<td> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audio/p286_028.mp3" type="audio/mpeg"></audio> </td>
<td> <audio controls id="player" onplay="pauseOthers(this);"><source src="assets/audio/res246049.mp3" type="audio/mpeg"></audio> </td>
</tr>
</table>

<p>&nbsp;</p> 


## Mel-Spectrogram Samples in One-shot VC

<div style="text-align: center;">
<img src="assets/mel/mel007.png" width = 1000 />
</div>
<p align="center">Figure.2 VC task "<i>The rainbow is a division of white light into many beautiful colors.</i>"</p>

<div style="text-align: center;">
<img src="assets/mel/mel010.png" width = 1000 />
</div>
<p align="center">Figure.3 VC task "<i>People look, but no one finds it.</i>"</p>

<div style="text-align: center;">
<img src="assets/mel/mel013.png" width = 1000 />
</div>
<p align="center">Figure.4 VC task "<i>Some have accepted it as a miracle without physical explanation.</i>"</p>

<p>&nbsp;</p> 



<p>&nbsp;</p> 



