<h1 id="tmuxcheatsheet">tmux cheat sheet</h1>

<p>(C-x means ctrl+x, M-x means alt+x)</p>

<h2 id="prefixkey">Prefix key</h2>

<p>The default prefix is C-b. If you (or your muscle memory) prefer C-a, you need to add this to <code>~/.tmux.conf</code>:</p>

<pre><code># remap prefix to Control + a
set -g prefix C-a
# bind 'C-a C-a' to type 'C-a'
bind C-a send-prefix
unbind C-b
</code></pre>

<p>I'm going to assume that C-a is your prefix.</p>

<h2 id="sessionswindowspanes">Sessions, windows, panes</h2>

<p>Session is a set of windows, plus a notion of which window is current.</p>

<p>Window is a single screen covered with panes. (Once might compare it to a ‘virtual desktop’ or a ‘space’.)</p>

<p>Pane is a rectangular part of a window that runs a specific command, e.g. a shell.</p>

<h2 id="gettinghelp">Getting help</h2>

<p>Display a list of keyboard shortcuts:</p>

<pre><code>C-a ?
</code></pre>

<p>Navigate using Vim or Emacs shortcuts, depending on the value of <code>mode-keys</code>. Emacs is the default, and if you want Vim shortcuts for help and copy modes (e.g. j, k, C-u, C-d), add the following line to <code>~/.tmux.conf</code>:</p>

<pre><code>setw -g mode-keys vi
</code></pre>

<p>Any command mentioned in this list can be executed as <code>tmux something</code> or <code>C-a :something</code> (or added to <code>~/.tmux.conf</code>).</p>

<h2 id="managingsessions">Managing sessions</h2>

<p>Creating a session:</p>

<pre><code>tmux new-session -s work
</code></pre>

<p>Create a new session that shares all windows with an existing session, but has its own separate notion of which window is current:</p>

<pre><code>tmux new-session -s work2 -t work
</code></pre>

<p>Attach to a session:</p>

<pre><code>tmux attach -t work
</code></pre>

<p>Detach from a session: <code>C-a d</code>.</p>

<p>Switch between sessions:</p>

<pre><code>C-a (          previous session
C-a )          next session
C-a L          ‘last’ (previously used) session
C-a s          choose a session from a list
</code></pre>

<p>Other:</p>

<pre><code>C-a $          rename the current session
C-a
</code></pre>

<h2 id="managingwindows">Managing windows</h2>

<p>Create a window:</p>

<pre><code>C-a c          create a new window
</code></pre>

<p>Switch between windows:</p>

<pre><code>C-a 1 ...      switch to window 1, ..., 9, 0
C-a 9
C-a 0
C-a p          previous window
C-a n          next window
C-a l          ‘last’ (previously used) window
C-a w          choose window from a list
</code></pre>

<p>Switch between windows with a twist:</p>

<pre><code>C-a M-n        next window with a bell, activity or
               content alert
C-a M-p        previous such window
</code></pre>

<p>Other:</p>

<pre><code>C-a ,          rename the current window
C-a &amp;          kill the current window
</code></pre>

<h2 id="managingsplitpanes">Managing split panes</h2>

<p>Creating a new pane by splitting an existing one:</p>

<pre><code>C-a "          split vertically (top/bottom)
C-a %          split horizontally (left/right)
</code></pre>

<p>Switching between panes:</p>

<pre><code>C-a left       go to the next pane on the left
C-a right      (or one of these other directions)
C-a up
C-a down
C-a o          go to the next pane (cycle through all of them)
C-a ;          go to the ‘last’ (previously used) pane
</code></pre>

<p>Moving panes around:</p>

<pre><code>C-a {          move the current pane to the previous position
C-a }          move the current pane to the next position
C-a C-o        rotate window ‘up’ (i.e. move all panes)
C-a M-o        rotate window ‘down’
C-a !          move the current pane into a new separate
               window (‘break pane’)
C-a :move-pane -t :3.2
               split window 3's pane 2 and move the current pane there
</code></pre>

<p>Resizing panes:</p>

<pre><code>C-a M-up, C-a M-down, C-a M-left, C-a M-right
               resize by 5 rows/columns
C-a C-up, C-a C-down, C-a C-left, C-a C-right
               resize by 1 row/column
</code></pre>

<p>Applying predefined layouts:</p>

<pre><code>C-a M-1        switch to even-horizontal layout
C-a M-2        switch to even-vertical layout
C-a M-3        switch to main-horizontal layout
C-a M-4        switch to main-vertical layout
C-a M-5        switch to tiled layout
C-a space      switch to the next layout
</code></pre>

<p>Other:</p>

<pre><code>C-a x          kill the current pane
C-a q          display pane numbers for a short while
</code></pre>

<h2 id="otherconfigfilesettings">Other config file settings</h2>

<p>Force a reload of the config file on C-a r:</p>

<pre><code>unbind r
bind r source-file ~/.tmux.conf
</code></pre>

<p>Some other settings that I use:</p>

<pre><code>setw -g xterm-keys on
</code></pre>