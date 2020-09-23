<div align="center">

## Make Internet Explorer Load Pages Faster


</div>

### Description

Improving Internet Explorer performance when browsing PSC or any site for that matter.<BR>
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Kevin Pirkl](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/kevin-pirkl.md)
**Level**          |Intermediate
**User Rating**    |5.0 (70 globes from 14 users)
**Compatibility**  |ASP \(Active Server Pages\) 
**Category**       |[Internet/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-html__1-34.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/kevin-pirkl-make-internet-explorer-load-pages-faster__1-21576/archive/master.zip)





### Source Code

For Internet Explorer (IE) users.<BR><BR>
Getting tired of waiting for that PSC web page to load in IE. Have you ever noticed the status bar at the bottom of your Internet Explorer screen when viewing PSC web pages says something like downloading 1.. of 50 files. Well as it turns out IE supports this nasty RFC 2068 that limits the number of simultaneous connections to a web site making your browsing experience slow beyond belief. Well my friends you can bypass this little setting with the nice little registry addition mentioned below. The following text is taken directly from Microsoft Article ID: Q183110<BR><BR>
"WinInet will limit connections to a single HTTP 1.0 server to four simultaneous connections. Connections to a single HTTP 1.1 server will be limited to two simultaneous connections. The HTTP 1.1 specification (RFC2068) mandates the two connection limit while the four connection limit for HTTP 1.0 is a self-imposed restriction which coincides with the standard used by a number of popular Web browsers. "<BR><BR>
For those of you that tend to open 2,3 or even a dozen browser screens while looking at PSC code/articles you will love the performance hike you see by making this change.<BR><BR>
As with anything you do to a computer making registry changes with regedit can be destructive so I take no responsibility if you break something. If you dont know how to use Regedit ask someone that does.<BR><BR>
For those of you looking to get even more performance when browsing the PSC site see the tweaks below. I recommend using image placeholders when rendering images, which will allow the page to render much more quickly.<BR><BR>
<A HREF=http://support.microsoft.com/support/kb/articles/Q183/1/10.ASP>INFO: WinInet Limits Connections Per Server
</A><BR><BR>
<A HREF=http://support.microsoft.com/support/kb/articles/Q153/7/90.asp>How to Improve Browsing Performance in Internet Explorer</A>

