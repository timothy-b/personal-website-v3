<script>
    import { dev } from '$app/environment';
    import ListSubItem from './ListSubItem.svelte';
</script>

<p>These have all had a profound impact on the way I approach software development and work relationships.</p>
<ul>
    <li><a href="https://echelonfront.com/extreme-ownership/">Extreme Ownership</a> by Jocko Willink</li>
    <li><a href="https://www.joelonsoftware.com/2000/03/21/converting-capital-into-software-that-works/">Converting Capital Into Software That Works</a> by Joel Spolsky</li>
        <ListSubItem>
            "A software company has to think of recruiting the right people as its <b>number one problem</b>. If you are successful, this can solve any other problem. Hire smart people, and they will produce good stuff that you can sell and make money off. Then everything else follows."
        </ListSubItem>
    <li><a href="https://www.joelonsoftware.com/2000/03/23/command-and-conquer-and-the-herd-of-coconuts/">Command and Conquer and the Herd of Coconuts</a> by Joel Spolsky</li>
    <li><a href="https://www.joelonsoftware.com/2002/02/13/the-iceberg-secret-revealed/">The Iceberg Secret, Revealed</a> by Joel Spolsky</li>
    <li><a href="https://www.joelonsoftware.com/2001/10/14/in-defense-of-not-invented-here-syndrome/">In defense of not-invented-here Syndrome</a> by Joel Spolsky</li>
        <ListSubItem>
            "If it's a core business function — do it yourself, no matter what."
        </ListSubItem>
    <li><a href="https://www.joelonsoftware.com/2001/05/05/what-is-the-work-of-dogs-in-this-country/">What is the Work of Dogs in this Country?</a> by Joel Spolsky</li>
        <ListSubItem>
            "Sometimes you download software and you just can't believe how bad it is, or how hard it is to accomplish the very simple tasks that the software tries to accomplish. Chances are, it's because the developers of the software don't use it."
        </ListSubItem>
    <li><a href="https://chademeng.com/me/do-the-right-thing-wait-to-get-fired/">Do the Right Thing and Wait to Get Fired</a> by Chade-Meng Tan</li>
    <li><a href="https://mcfunley.com/choose-boring-technology">Choose Boring Technology</a> by Dan McKinley</li>
    <li><a href="https://livebook.manning.com/book/functional-programming-in-scala/">Functional Programming in Scala</a> by Rúnar Bjarnason and Paul Chiusano</li>
    <li><a href="https://echelonfront.com/dichotomy-of-leadership/">The Dichotomy of Leadership</a> by Jocko Willink</li>
    <li><a href="https://firesomeonetoday.com/">Fire Someone Today</a> by Bob Pritchett</li>
    <li><a href="https://www.goodreads.com/en/book/show/151881">A Failure of Nerve: Leadership in the Age of the Quick Fix</a> by Edwin H. Friedman</li>
    <li><a href="https://startnextnow.com/">Start Next Now</a> by Bob Pritchett</li>
    <li><a href="https://samnewman.io/books/building_microservices/">Building Microservices</a> by Sam Newman</li>
</ul>

{#if dev}
    <a href="/" rel="external">back</a>
{:else}
    <a href="/v3/" rel="external">back</a>
{/if}
