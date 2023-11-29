<script>
    import { dev } from '$app/environment';
    import ItalicListSubItem from '../../components/ItalicListSubItem.svelte';
</script>

<p>These have all had a profound impact on the way I approach software development and work relationships.</p>
<ul>
    <li><a href="https://echelonfront.com/extreme-ownership/">Extreme Ownership</a> by Jocko Willink</li>
    <li><a href="https://www.joelonsoftware.com/2000/03/21/converting-capital-into-software-that-works/">Converting Capital Into Software That Works</a> by Joel Spolsky</li>
        <ItalicListSubItem>
            "A software company has to think of <b>recruiting the right people</b> as its <b>number one problem</b>. If you are successful, this can solve any other problem. Hire smart people, and they will produce good stuff that you can sell and make money off. Then everything else follows."
        </ItalicListSubItem>
    <li><a href="https://learn.microsoft.com/en-us/archive/blogs/ericlippert/gretchen-and-zoe-are-cool">Gretchen and Zoe are Cool</a> by Eric Lippert</li>
        <ItalicListSubItem>
            "There is <b>nothing</b> more crucial to the long-term health of a software business than hiring the right people. Ironically, that is a highly non-technical problem!"
        </ItalicListSubItem>
    <li><a href="https://www.joelonsoftware.com/2000/03/23/command-and-conquer-and-the-herd-of-coconuts/">Command and Conquer and the Herd of Coconuts</a> by Joel Spolsky</li>
        <ItalicListSubItem>
            "If you hire all A people, he said, they'll also hire A people. But if you hire B people, they'll hire the C people and then it's all over."
        </ItalicListSubItem>
    <li><a href="https://faithlife.codes/blog/2023/09/rest-level-zero-dot-five/">REST Level 0.5</a> by Erik Lanning</li>
        <ItalicListSubItem>
            "I've read several articles about REST, even a bit of the original paper. But I still have quite a vague idea about what it is. I'm beginning to think that nobody knows, that it's simply a very poorly defined concept. Like Web 2.0, everyone talked about it but nobody could give a clear definition. Thoughts?" - RivieraKid
        </ItalicListSubItem>
    <li><a href="https://www.joelonsoftware.com/2002/02/13/the-iceberg-secret-revealed/">The Iceberg Secret, Revealed</a> by Joel Spolsky</li>
        <ItalicListSubItem>
            "If you show a nonprogrammer a screen which has a user interface that is 90% worse, they will think that the program is 90% worse."
        </ItalicListSubItem>
    <li><a href="https://www.joelonsoftware.com/2001/10/14/in-defense-of-not-invented-here-syndrome/">In defense of not-invented-here Syndrome</a> by Joel Spolsky</li>
        <ItalicListSubItem>
            "If it's a core business function — do it yourself, no matter what."
        </ItalicListSubItem>
    <li><a href="https://www.joelonsoftware.com/2001/05/05/what-is-the-work-of-dogs-in-this-country/">What is the Work of Dogs in this Country?</a> by Joel Spolsky</li>
        <ItalicListSubItem>
            "Sometimes you download software and you just can't believe how bad it is, or how hard it is to accomplish the very simple tasks that the software tries to accomplish. Chances are, it's because the developers of the software don't use it."
        </ItalicListSubItem>
    <li><a href="https://chademeng.com/me/do-the-right-thing-wait-to-get-fired/">Do the Right Thing and Wait to Get Fired</a> by Chade-Meng Tan</li>
    <li><a href="https://mcfunley.com/choose-boring-technology">Choose Boring Technology</a> by Dan McKinley</li>
    <li><a href="https://livebook.manning.com/book/functional-programming-in-scala/">Functional Programming in Scala</a> by Rúnar Bjarnason and Paul Chiusano</li>
    <li><a href="https://echelonfront.com/dichotomy-of-leadership/">The Dichotomy of Leadership</a> by Jocko Willink</li>
    <li><a href="https://firesomeonetoday.com/">Fire Someone Today</a> by Bob Pritchett</li>
    <li><a href="https://www.goodreads.com/en/book/show/151881">A Failure of Nerve: Leadership in the Age of the Quick Fix</a> by Edwin H. Friedman</li>
    <li><a href="https://startnextnow.com/">Start Next Now</a> by Bob Pritchett</li>
    <li><a href="https://blog.3d-logic.com/2023/10/17/accelerate-your-software-engineering-career-by-fixing-something-every-week/">Accelerate your software engineering career by fixing something every week.</a> by Pawel Kadluczka</li>
    <li><a href="https://samnewman.io/books/building_microservices/">Building Microservices</a> by Sam Newman</li>
</ul>

{#if dev}
    <a href="/" rel="external">back</a>
{:else}
    <a href="/v3/" rel="external">back</a>
{/if}

<style>
    li::before {
        content: " ";
        display: block;
        margin-top: 0.5em;
    }
</style>