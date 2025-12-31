<script>
    import { dues } from '$lib/utils/helper';
    let one, oneOne, oneOneOne, oneTwo, oneTwoOne, oneTwoTwo, oneTwoThree, oneTwoFour, oneTwoFive, oneThree;
    let two, twoOne, twoTwo, twoThree;
    let three, threeOne;
    let four, fourOne, fourTwo;
    let five, fiveOne;
    let six, sixOne, sixTwo, sixThree;
    let seven, sevenOne, sevenTwo, sevenThree;

    const goToSection = (section) => {
        const top = section.getBoundingClientRect().top + window.pageYOffset;
        window.scrollTo({left: 0, top, behavior: 'smooth'});
    }
</script>

<style>
    .constitution {
        position: relative;
        z-index: 1;
        width: 92%;
        max-width: 800px;
        margin: 8em auto 10em;
    }

    h1 {
        font-size: 2em;
        line-height: 1.2em;
        text-align: center;
        margin: 2em 0 1.5em;
    }

    h2 {
        font-size: 1.5em;
        line-height: 1.2em;
    }

    h3 {
        text-decoration: underline;
        font-size: 1.3em;
        line-height: 1.2em;
    }

    h4 {
        text-decoration: underline;
        margin-left: 2em;
        font-size: 1.2em;
        line-height: 1.2em;
    }

    h5 {
        margin-left: 6em;
        font-size: 0.8em;
        line-height: 1.1em;
    }

    .subBlock {
        margin-left: 2.4em;
    }

    .sectionHeading {
        margin: 4em 0 1.5em;
    }

    .subSectionHeading {
        margin: 1.5em 0 1.5em;
    }

    .underscore {
        text-decoration: underline;
    }

    .right {
        text-align: right;
    }

    .positionMaximums td {
        min-width: 3em;
    }

    .noUnderscore {
        text-decoration: none;
    }

    .clickable {
        cursor: pointer;
    }

    .clickable:hover {
        color: #00316b;
    }

    p {
        color: #777;
    }
</style>

<div class="constitution">
    <h1 class="noUnderscore">NATIONAL DEGENERATES LEAGUE CONSTITUTION</h1>
    
    <h2 class="sectionHeading" bind:this={one}>Section 1 Roster Breakdown</h2>
    
    <h3 class="subSectionHeading" bind:this={oneOne}>1.1 Positional Breakdown</h3>
    
    <p>14 Total Players</p>
    
    <p class="underscore">Starters</p>
    <ul>
        <li>QB</li>
        <li>RB</li>
        <li>RB</li>
        <li>WR</li>
        <li>WR</li>
        <li>TE</li>
        <li>FLEX (RB/WR/TE)</li>
        <li>K</li>
        <li>D/ST</li>
    </ul>
    
    <p>5 Bench</p>

    <p>1 IR Spots (Player must be labeled as IR in the Sleeper App)</p>
    
    <h3 class="subSectionHeading" bind:this={oneTwo}>1.2 Trading</h3>
    
    <p>All trades will be pending for a period of 1 day (24 hours) from the time of the trade submission. During this period, Managers have the opportunity to vote on whether or not to veto the trade. To veto a trade, Members must cast their vote if they wish to do so. A trade will be considered vetoed if a majority of greater than 5 out of 10 Members vote against it. It is at the commissioners sole discretion to manually process the trade once majority vote is reached.</p>
    
    <h4 bind:this={oneTwoOne}>1.2.1 Trade Collusion</h4>
    <div class="subBlock">
        <p>If any owners are suspected of accepting bribes/offering bribes to enhance their/another owners team via trade, trading any assets other than fantasy players, draft picks, or otherwise found guilty of engaging in any form of collusion*, all parties involved in the trade will be susceptible to punishment. The punishments will go as followed:</p>
        
        <ul>
            <li>First Offense – Immediate freeze on all transaction types for the next 18 weeks of regular season and playoff fantasy football games, including trades and waiver wire bids</li>
            <li>Second Offense – A league meeting of all members not involved in any of the improper trades/activity in question will take place to discuss next steps.</li>
        </ul>

        <p>All trades that are found guilty of collusion, will be reversed/denied. If the trade had affected the outcome of previous games, the results of those games will be revised.  </p>

        <p>*Collusion includes the organizing of veto votes against an acceptable trade.</p>

        <p>The commissioner will err on the side of letting owners manage their teams the way they see fit. Any collusion will need to be clear. The commissioner reserves the right to step in and at the very least assess the thinking of any team involved in a heavily lop-sided trade. </p>
    </div>

    <h4 bind:this={oneTwoTwo}>1.2.2 Lending Players Prohibition</h4>
    <div class="subBlock">
        <p>Any player traded from a team may not be re-acquired via trade within 6 weeks of the original trade. Any teams involved in this behavior will be subject to the aforementioned collusion punishments.</p>
    </div>
    
    <h4 bind:this={oneTwoThree}>1.2.3 Trade Deadline</h4>
    <div class="subBlock">
        <p>The trade deadline will be set for week 11 games of the NFL regular season.</p>
    </div>
    
    <h4 bind:this={oneTwoFour}>1.2.4 Veto/Trade Process</h4>
    <div class="subBlock">
        <p>A total of 5 veto votes are required to veto a trade. Vetoes are only appropriate in instances of collusion or an egregious mismatch of value. Not liking a trade does not warrant a veto.</p>
    </div>

     <h4 bind:this={oneTwoFive}>1.2.5 Majority Rule Clause</h4>
    <div class="subBlock">
        <p>In the event that any manager encounters an unusual situation or dispute during the season, they have the right to bring the issue before the league for consideration. Each manager may call for a majority vote to resolve the matter. To initiate this process, the concerned manager or managers must present a detailed description of the issue to all league managers. A vote will then be conducted, and a resolution will be determined by a simple majority. In the unusual event of a tie vote, the team in last place at the time of the vote will not be counted towards the majority vote. All managers are required to participate in the voting process to ensure a fair and democratic resolution.</p>
    </div>
    
    <h2 class="sectionHeading" bind:this={two}>Section 2 Drafting</h2>

    <h3 bind:this={twoOne}>2.1 Draft Day Availability</h3>
    <p>All Members must be present at their devices for the draft. Auto-draft will not be permitted unless strenuous circumstances prohibit the Member from participating in the draft. These circumstances will be presented to the Commissioner and it is at his sole discretion whether or not the circumstances constitute as strenuous in nature.</p>

    <h3 bind:this={twoTwo}>2.2 Draft Order</h3>
    <p>The draft order each year will be set at random 24 hours ahead of the scheduled draft. In the event that the draft must be rescheduled after the draft order has been randomized, it is at the sole discretion of the commissioner whether or not to re-randomize the draft order.</p>
    
    <h3 bind:this={twoThree}>2.3 Draft Day Trades</h3>
    <p>Draft Day Trades are not permitted.</p>

    
    <h2 class="sectionHeading" bind:this={three}>Section 3 Scoring System</h2>

    <h3 bind:this={threeOne}>3.1 Scoring System</h3>
    <p>The league scoring system breakdown is listed on the Sleeper fantasy app (for the most part, it follows typical 1PPR Scoring). The scoring system will never change without a majority league vote.</p>
    
    <h2 class="sectionHeading" bind:this={four}>Section 4 Postseason</h2>
    
    <h3 bind:this={fourOne}>4.1 Playoffs</h3>
    <p>At the end of the season 6 teams will make the playoffs. The first round of playoffs will commence in week 15. The 6 teams that finish with the best records through week 14 will receive a playoff berth. The 2 teams with the best records through week 14 will receive a bye week in the first round of the playoffs. Each playoff matchup will only last one week and the winner will advance. Week 18 will not be used.</p>
    
    <h3 bind:this={fourTwo}>4.2 Seeding Tiebreakers</h3>
    <p>If two teams finish with the same record the tiebreakers will go as followed:</p>

    <ol>
        <li>Points For</li>
        <li>Head 2 Head Record</li>
        <li>Division Record</li>
        <li>Total Points Against</li>
        <li>Coin Flip</li>
        <li>Duel to the death</li>
    </ol>

    <h2 class="sectionHeading" bind:this={five}>Section 5 Tanking Policy</h2>
    
    <h3 bind:this={fiveOne}>5.1 League Tanking Policy</h3>
    <p>No team may intentionally leave starting roster spots empty. Any evidence of intentionally leaving roster spots empty may be subject to punishment, including but not limited to the forfeiture of lineup changes or waiver wire privelages. It is at the commissioners sole discretion, at any time, to set a Managers lineup if any roster spots are left empty. </p>
    <p>To maintain competitive balance and fairness, managers are prohibited from intentionally releasing high-value players or a significant portion of their roster in a manner that provides an unfair advantage to other teams. Legitimate roster moves, such as dropping players due to injury, suspension, or poor performance, are allowed. Any actions deemed to be "dumping" or collusion will be subject to review by the league commissioner, who has the authority to reverse roster changes, lock dropped players on waivers, and impose penalties, including loss of waiver privileges, draft picks, or removal from the league for severe violations. Complaints of potential dumping must be submitted to the commissioner with supporting evidence for review.</p>

    <h2 class="sectionHeading" bind:this={six}>Section 6 Replacing Managers</h2>
    
    <h3 bind:this={sixOne}>6.1 Removing Managers</h3>
    <p>Short of continuously failing to set a valid lineup, or confirmed collusion, no manager can be removed against their will. Participation, through the league chat, trade offers, and the waiver wire, is strongly encouraged but generally grounds for removal.</p>
    
    <h3 bind:this={sixTwo}>6.2 Replacing Managers</h3>
    <p>When a manager needs to be replaced, the commisiooners will try to find a suitable candidate with some connection to at least a portion of the existing managers. Priority will be placed on managers who are eager to take on a commitment and will be very active within the league.</p>

    <h2 class="sectionHeading" bind:this={seven}>Section 7 League Finances</h2>
    
    <h3 bind:this={sevenOne}>7.1 League Dues</h3>
    <p>League dues are set at {dues}$. Dues are collected through Venmo (@haydenjacobsen). All managers must be fully paid up before the start of regular season. In the event that a manager fails to pay before the deadline, a 10% penalty will be added to their payment and will go towards the payouts at the end of the year.</p>
    
    <h3 bind:this={sevenTwo}>7.2 Payout</h3>
    <p>League payout is structured as follows:</p>
    <ul>
        <li>1st place: {dues * 6.5}$</li>
        <li>2nd place: {dues * 2.5}$</li>
        <li>3rd place: {dues}$</li>
    </ul>
    <p>In the event that a manager was fined due to late payment, their extra fee will be added to the winner's payout.</p>


    <h2 class="sectionHeading" bind:this={eight}>Section 8 Pre-Game Ritual</h2>

    <h3 bind:this={eightOne}>8.1 Weekly Shot/Shotgun</h3>
    <p>Each week, the manager with the lowest scoring points must take a shot or shotgun before the first snap of the following week's first game. Each manager is individually responsible for keeping track of who had the lowest scoring week and when the first game of the following week will take place.  A video of this action must be recorded and sent to the league group chat or designated platform as proof. If a Manager fails to take the shot/shotgun and send the video before the first snap, their highest-scoring player for that week will be benched. Each week the Manager does not take their shot/shotgun before the first snap of the following week’s first game, another shot/shotgun will be added on. Players who are benched by the commissioner will still be considered towards a manager's total score for that week.

    <h2 class="sectionHeading" bind:this={nine}>Section 9 Last Place Punishment</h2>

    <h3 bind:this={nineOne}>9.1 Last Place Punishment</h3>
    <p>The punishment for the league loser will be determined by a majority vote of the managers before the draft. The punishment receiving the most votes will be adopted. The league loser must complete the agreed-upon punishment before the start of the following season. Members who fail to complete the punishment will be prohibited from participating in the league for the subsequent season.

</div>
