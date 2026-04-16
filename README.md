<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>SMSF Property Strategy Guide | Quantum Buyers Agents</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap');

    body {
      font-family: 'Inter', sans-serif;
      background: #ffffff;
      color: #000000;
      scroll-behavior: smooth;
    }

    .section-block {
      padding-top: 6rem;
      padding-bottom: 6rem;
      border-bottom: 1px solid #ece7e1;
    }

    .section-block:last-child {
      border-bottom: none;
    }

    .premium-card {
      background: #ffffff;
      border: 1px solid #d9d3cb;
      transition: all 0.25s ease;
    }

    .premium-card:hover {
      border-color: #7a3e04;
      transform: translateY(-2px);
    }

    .nav-link {
      position: relative;
      padding-bottom: 2px;
    }

    .nav-link::after {
      content: '';
      position: absolute;
      left: 0;
      bottom: 0;
      width: 0;
      height: 1px;
      background: #7a3e04;
      transition: width 0.25s ease;
    }

    .nav-link:hover::after {
      width: 100%;
    }

    .accent-line {
      width: 48px;
      height: 2px;
      background: #7a3e04;
    }

    .chart-wrap {
      position: relative;
      width: 100%;
      height: 320px;
    }
  </style>
</head>
<body class="antialiased">
  <nav class="fixed top-0 w-full z-50 bg-white/90 backdrop-blur-md border-b border-stone-200">
    <div class="max-w-7xl mx-auto px-6 h-20 flex items-center justify-between">
      <div class="flex items-center gap-3">
        <div class="w-9 h-9 bg-black rounded-sm flex items-center justify-center">
          <div class="w-4 h-4 border border-[#7a3e04] rotate-45"></div>
        </div>
        <div>
          <div class="text-[10px] uppercase tracking-[0.28em] text-stone-500 font-semibold">Quantum Buyers Agents</div>
          <div class="text-sm font-bold tracking-tight text-black">Property Strategy</div>
        </div>
      </div>
      <div class="hidden md:flex items-center gap-8 text-[11px] uppercase tracking-[0.2em] text-stone-500 font-semibold">
        <a href="#overview" class="nav-link hover:text-black">Overview</a>
        <a href="#rules" class="nav-link hover:text-black">Rules</a>
        <a href="#borrowing" class="nav-link hover:text-black">Borrowing</a>
        <a href="#process" class="nav-link hover:text-black">Process</a>
        <a href="#contact" class="nav-link hover:text-black">Contact</a>
      </div>
    </div>
  </nav>

  <header class="relative pt-36 pb-24 md:pt-48 md:pb-32 bg-black overflow-hidden">
    <div class="absolute inset-0 opacity-[0.08]" style="background-image: radial-gradient(#ffffff 1px, transparent 1px); background-size: 34px 34px;"></div>
    <div class="max-w-7xl mx-auto px-6 relative z-10">
      <div class="max-w-4xl">
        <p class="text-[#b0a395] text-xs uppercase tracking-[0.32em] font-bold mb-6">SMSF Property Guide</p>
        <h1 class="text-white text-5xl md:text-7xl font-extrabold leading-[1.02] tracking-tight mb-8">
          SMSF Property<br />
          <span class="text-stone-400">Strategy Guide</span>
        </h1>
        <div class="accent-line mb-8"></div>
        <p class="text-xl md:text-2xl text-stone-300 font-light leading-relaxed max-w-3xl mb-10">
          How high income Australians are using super to acquire property assets strategically. Structured. Compliant. Long term focused.
        </p>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-4 mb-10 max-w-4xl">
          <div class="border border-white/10 bg-white/5 p-4">
            <div class="text-[10px] uppercase tracking-[0.24em] text-stone-500 font-bold mb-2">Built for</div>
            <div class="text-white font-semibold">Investors seeking control over retirement outcomes</div>
          </div>
          <div class="border border-white/10 bg-white/5 p-4">
            <div class="text-[10px] uppercase tracking-[0.24em] text-stone-500 font-bold mb-2">Focus</div>
            <div class="text-white font-semibold">Education first. Strategy second. Compliance always.</div>
          </div>
          <div class="border border-white/10 bg-white/5 p-4">
            <div class="text-[10px] uppercase tracking-[0.24em] text-stone-500 font-bold mb-2">Important</div>
            <div class="text-white font-semibold">General information only. Not financial advice.</div>
          </div>
        </div>
        <div class="flex flex-col sm:flex-row gap-4">
          <a href="#contact" class="inline-flex items-center justify-center bg-[#7a3e04] hover:bg-[#643200] text-white px-7 py-4 text-sm font-bold uppercase tracking-[0.18em] transition-colors">Book a Strategy Call</a>
          <a href="#process" class="inline-flex items-center justify-center border border-white/15 text-white hover:bg-white hover:text-black px-7 py-4 text-sm font-bold uppercase tracking-[0.18em] transition-colors">See the Process</a>
        </div>
      </div>
    </div>
  </header>

  <main>
    <section id="overview" class="section-block max-w-7xl mx-auto px-6">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-16">
        <div class="lg:col-span-4">
          <p class="text-[#7a3e04] text-xs uppercase tracking-[0.28em] font-bold mb-5">Overview</p>
          <h2 class="text-4xl font-bold text-black mb-6">Before You Go Further</h2>
          <p class="text-stone-600 leading-relaxed font-light mb-6">
            SMSF property is one of the most regulated strategies in Australia. Done correctly, it can be powerful. Done incorrectly, it can be expensive.
          </p>
          <p class="text-stone-600 leading-relaxed font-light">
            This page is designed to help you understand the structure, the rules, the costs, and the process before making any decisions.
          </p>
        </div>
        <div class="lg:col-span-8 grid grid-cols-1 md:grid-cols-2 gap-8">
          <div class="premium-card p-10 border-l-4 border-l-[#7a3e04]">
            <div class="text-[10px] uppercase tracking-[0.24em] text-stone-400 font-bold mb-5">What this does</div>
            <h3 class="text-2xl font-bold mb-5">What this guide covers</h3>
            <ul class="space-y-4 text-stone-600 text-sm font-light">
              <li class="flex items-start gap-3"><span class="w-1.5 h-1.5 bg-[#7a3e04] rounded-full mt-2"></span><span>How SMSF property investment works in plain English</span></li>
              <li class="flex items-start gap-3"><span class="w-1.5 h-1.5 bg-[#7a3e04] rounded-full mt-2"></span><span>The major compliance rules you need to understand</span></li>
              <li class="flex items-start gap-3"><span class="w-1.5 h-1.5 bg-[#7a3e04] rounded-full mt-2"></span><span>The professionals involved and where each one fits</span></li>
            </ul>
          </div>
          <div class="premium-card p-10 border-l-4 border-l-black">
            <div class="text-[10px] uppercase tracking-[0.24em] text-stone-400 font-bold mb-5">What to do first</div>
            <h3 class="text-2xl font-bold mb-5">Start with the right advice</h3>
            <ul class="space-y-4 text-stone-600 text-sm font-light">
              <li class="flex items-start gap-3"><span class="w-1.5 h-1.5 bg-black rounded-full mt-2"></span><span>Speak with a licensed financial planner</span></li>
              <li class="flex items-start gap-3"><span class="w-1.5 h-1.5 bg-black rounded-full mt-2"></span><span>Confirm your structure with a qualified SMSF accountant</span></li>
              <li class="flex items-start gap-3"><span class="w-1.5 h-1.5 bg-black rounded-full mt-2"></span><span>Then bring in your mortgage broker for the borrowing side</span></li>
            </ul>
          </div>
        </div>
      </div>
      <div class="mt-14 border border-stone-200 bg-stone-50 p-8">
        <p class="text-sm text-stone-600 leading-relaxed text-center">
          This is general information only. It is not financial, tax, or legal advice, and it is not a recommendation to establish an SMSF or purchase property through one.
        </p>
      </div>
    </section>

    <section class="section-block bg-black text-white">
      <div class="max-w-7xl mx-auto px-6">
        <div class="text-center mb-20 max-w-3xl mx-auto">
          <p class="text-[#b0a395] text-xs uppercase tracking-[0.28em] font-bold mb-4">Structure</p>
          <h2 class="text-4xl font-bold mb-6">What Is an SMSF?</h2>
          <div class="accent-line mx-auto mb-6"></div>
          <p class="text-stone-400 font-light leading-relaxed">
            A Self Managed Super Fund gives you control over how your super is invested. Instead of a large super fund making the investment decisions, you and the fund members do.
          </p>
        </div>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-10">
          <div class="border-t border-white/15 pt-8">
            <div class="text-[#b0a395] text-xs uppercase tracking-[0.24em] font-bold mb-4">01. Control</div>
            <h3 class="text-xl font-bold mb-4">You choose the assets</h3>
            <p class="text-sm text-stone-400 font-light">That may include cash, shares, term deposits, and in some cases residential property.</p>
          </div>
          <div class="border-t border-white/15 pt-8">
            <div class="text-[#b0a395] text-xs uppercase tracking-[0.24em] font-bold mb-4">02. Members</div>
            <h3 class="text-xl font-bold mb-4">Up to six people</h3>
            <p class="text-sm text-stone-400 font-light">Family members can pool their balances together and invest through one fund.</p>
          </div>
          <div class="border-t border-white/15 pt-8">
            <div class="text-[#b0a395] text-xs uppercase tracking-[0.24em] font-bold mb-4">03. Strategy</div>
            <h3 class="text-xl font-bold mb-4">Long term focus</h3>
            <p class="text-sm text-stone-400 font-light">The asset must be held to support retirement outcomes, not for personal use or convenience.</p>
          </div>
          <div class="border-t border-white/15 pt-8">
            <div class="text-[#b0a395] text-xs uppercase tracking-[0.24em] font-bold mb-4">04. Compliance</div>
            <h3 class="text-xl font-bold mb-4">The rules are strict</h3>
            <p class="text-sm text-stone-400 font-light">This is not an area to improvise. Your accountant and legal team matter.</p>
          </div>
        </div>
      </div>
    </section>

    <section id="rules" class="section-block max-w-7xl mx-auto px-6">
      <div class="text-center max-w-3xl mx-auto mb-16">
        <p class="text-[#7a3e04] text-xs uppercase tracking-[0.28em] font-bold mb-4">Compliance</p>
        <h2 class="text-4xl font-bold mb-6">The Rules You Need to Know</h2>
        <p class="text-stone-600 font-light leading-relaxed">
          Most people do not get caught out by the market. They get caught out by the rules. These are the foundations that sit behind every compliant SMSF property purchase.
        </p>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-px bg-stone-200 border border-stone-200">
        <div class="bg-white p-10">
          <h3 class="text-xl font-bold mb-4">Sole Purpose Test</h3>
          <p class="text-sm text-stone-600 font-light leading-relaxed">The property must be held only for retirement purposes. That is the starting point for everything.</p>
        </div>
        <div class="bg-white p-10">
          <h3 class="text-xl font-bold mb-4">No Personal Use</h3>
          <p class="text-sm text-stone-600 font-light leading-relaxed">You cannot live in the property, holiday in it, or allow relatives to use it.</p>
        </div>
        <div class="bg-white p-10">
          <h3 class="text-xl font-bold mb-4">Arms Length Tenancy</h3>
          <p class="text-sm text-stone-600 font-light leading-relaxed">It must be rented to an unrelated tenant at market rent under normal commercial terms.</p>
        </div>
        <div class="bg-white p-10">
          <h3 class="text-xl font-bold mb-4">Third Party Purchase</h3>
          <p class="text-sm text-stone-600 font-light leading-relaxed">The property must be purchased from an unrelated seller, not you, not family, and not a related entity.</p>
        </div>
        <div class="bg-white p-10">
          <h3 class="text-xl font-bold mb-4">Fund Separation</h3>
          <p class="text-sm text-stone-600 font-light leading-relaxed">All income, expenses, and repayments must flow through the SMSF bank account, not your personal accounts.</p>
        </div>
        <div class="bg-[#7a3e04] p-10 flex items-center">
          <p class="text-white text-xs uppercase tracking-[0.2em] leading-loose font-bold">
            Breaking these rules can trigger penalties, tax consequences, and serious compliance issues for the fund.
          </p>
        </div>
      </div>
    </section>

    <section id="borrowing" class="section-block bg-stone-50">
      <div class="max-w-7xl mx-auto px-6">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-16 items-start">
          <div class="lg:col-span-5">
            <p class="text-[#7a3e04] text-xs uppercase tracking-[0.28em] font-bold mb-5">Borrowing</p>
            <h2 class="text-4xl font-bold mb-6">How the Borrowing Works</h2>
            <p class="text-stone-600 font-light leading-relaxed mb-8">
              Most SMSF property purchases that involve finance are done through an LRBA, or Limited Recourse Borrowing Arrangement. It sounds technical, but the idea is simple.
            </p>

            <div class="premium-card p-8 bg-white mb-8">
              <div class="text-[10px] uppercase tracking-[0.24em] text-stone-400 font-bold mb-4">In plain English</div>
              <ul class="space-y-4 text-sm text-stone-700 font-light">
                <li class="flex items-start gap-3"><span class="w-1.5 h-1.5 bg-[#7a3e04] rounded-full mt-2"></span><span>Your SMSF is buying the property</span></li>
                <li class="flex items-start gap-3"><span class="w-1.5 h-1.5 bg-[#7a3e04] rounded-full mt-2"></span><span>The bank lends to the SMSF under a specific structure</span></li>
                <li class="flex items-start gap-3"><span class="w-1.5 h-1.5 bg-[#7a3e04] rounded-full mt-2"></span><span>If things go wrong, the lender is generally limited to that property only</span></li>
              </ul>
            </div>

            <div class="space-y-6">
              <div class="flex gap-4">
                <div class="w-11 h-11 bg-black text-white rounded-full flex items-center justify-center text-xs font-bold shrink-0">01</div>
                <div>
                  <h3 class="font-bold mb-2">A bare trust holds the title</h3>
                  <p class="text-sm text-stone-600 font-light">A separate legal entity temporarily holds the property on trust for the SMSF until the loan is repaid.</p>
                </div>
              </div>
              <div class="flex gap-4">
                <div class="w-11 h-11 bg-[#7a3e04] text-white rounded-full flex items-center justify-center text-xs font-bold shrink-0">02</div>
                <div>
                  <h3 class="font-bold mb-2">The funding rules are tighter</h3>
                  <p class="text-sm text-stone-600 font-light">Interest rates are often higher, borrowing limits are more conservative, and major renovations generally cannot be funded through the LRBA.</p>
                </div>
              </div>
            </div>
          </div>

          <div class="lg:col-span-7">
            <div class="premium-card p-10 border-t-4 border-t-[#7a3e04] bg-white">
              <div class="text-[10px] uppercase tracking-[0.24em] text-stone-400 font-bold text-center mb-6">Structure snapshot</div>
              <div class="chart-wrap">
                <canvas id="lrbaChart"></canvas>
              </div>
              <div class="mt-10 bg-black text-white p-8 rounded-sm">
                <div class="text-[10px] uppercase tracking-[0.24em] text-[#b0a395] font-bold mb-4">Who sets this up</div>
                <p class="text-sm text-stone-300 font-light leading-relaxed">
                  Your accountant or lawyer handles the trust documents and legal structure. Your mortgage broker arranges the lending side and works with the lender to ensure the documentation is accepted before settlement.
                </p>
                <p class="mt-4 text-sm text-[#b0a395] font-semibold">
                  This structure must be established correctly before settlement. It is not optional.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="process" class="section-block max-w-7xl mx-auto px-6">
      <div class="text-center max-w-3xl mx-auto mb-16">
        <p class="text-[#7a3e04] text-xs uppercase tracking-[0.28em] font-bold mb-4">Process</p>
        <h2 class="text-4xl font-bold mb-6">What This Looks Like in the Real World</h2>
        <p class="text-stone-600 font-light leading-relaxed">
          This is not a low cost shortcut. It is a structured long term wealth strategy, and the process needs to be handled in the right order.
        </p>
      </div>

      <div class="space-y-4">
        <div class="border border-stone-200 p-8 flex flex-col md:flex-row gap-8 items-center hover:border-[#7a3e04] hover:bg-stone-50 transition-colors">
          <div class="text-5xl font-extrabold text-stone-200">01</div>
          <div class="flex-1">
            <h3 class="text-xl font-bold mb-2">Get strategic advice first</h3>
            <p class="text-sm text-stone-600 font-light">Start with your financial planner and SMSF accountant. Confirm whether this is suitable before you even think about property selection.</p>
          </div>
        </div>
        <div class="border border-stone-200 p-8 flex flex-col md:flex-row gap-8 items-center hover:border-[#7a3e04] hover:bg-stone-50 transition-colors">
          <div class="text-5xl font-extrabold text-stone-200">02</div>
          <div class="flex-1">
            <h3 class="text-xl font-bold mb-2">Build the fund position</h3>
            <p class="text-sm text-stone-600 font-light">Ensure the SMSF has enough for the deposit, purchase costs, setup costs, and an ongoing buffer for vacancies and expenses.</p>
          </div>
        </div>
        <div class="border border-stone-200 p-8 flex flex-col md:flex-row gap-8 items-center hover:border-[#7a3e04] hover:bg-stone-50 transition-colors">
          <div class="text-5xl font-extrabold text-stone-200">03</div>
          <div class="flex-1">
            <h3 class="text-xl font-bold mb-2">Sort the lending and legal structure</h3>
            <p class="text-sm text-stone-600 font-light">Your broker, accountant, and legal team work together to prepare the LRBA and bare trust correctly before settlement.</p>
          </div>
        </div>
        <div class="border border-stone-200 p-8 flex flex-col md:flex-row gap-8 items-center hover:border-[#7a3e04] hover:bg-stone-50 transition-colors">
          <div class="text-5xl font-extrabold text-stone-200">04</div>
          <div class="flex-1">
            <h3 class="text-xl font-bold mb-2">Source the right property</h3>
            <p class="text-sm text-stone-600 font-light">The property needs to make sense from both a compliance perspective and an investment perspective, not just because it looks good on paper.</p>
          </div>
        </div>
        <div class="border border-stone-200 p-8 flex flex-col md:flex-row gap-8 items-center hover:border-[#7a3e04] hover:bg-stone-50 transition-colors">
          <div class="text-5xl font-extrabold text-stone-200">05</div>
          <div class="flex-1">
            <h3 class="text-xl font-bold mb-2">Settle, manage, and stay compliant</h3>
            <p class="text-sm text-stone-600 font-light">From there, the fund continues to manage rent, expenses, reporting, and annual audit obligations through the correct SMSF channels.</p>
          </div>
        </div>
      </div>
    </section>

    <section class="section-block bg-black text-white">
      <div class="max-w-7xl mx-auto px-6">
        <div class="text-center max-w-3xl mx-auto mb-16">
          <p class="text-[#b0a395] text-xs uppercase tracking-[0.28em] font-bold mb-4">Costs</p>
          <h2 class="text-4xl font-bold mb-6">What Does It Cost?</h2>
          <div class="accent-line mx-auto mb-6"></div>
          <p class="text-stone-400 font-light leading-relaxed">
            This is not a low cost strategy. It is a long term wealth strategy. Most investors only look seriously at this once they have a meaningful super balance and a clear reason for doing it.
          </p>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-2 gap-16 items-center">
          <div class="space-y-10">
            <div class="border-l-2 border-[#7a3e04] pl-8">
              <div class="text-4xl font-bold mb-2">$3K+</div>
              <h3 class="text-lg font-bold text-[#b0a395] mb-2">Setup costs</h3>
              <p class="text-sm text-stone-400 font-light">SMSF establishment, trust structuring, and related legal documentation can vary depending on complexity.</p>
            </div>
            <div class="border-l-2 border-[#7a3e04] pl-8">
              <div class="text-4xl font-bold mb-2">$2K+</div>
              <h3 class="text-lg font-bold text-[#b0a395] mb-2">Annual running costs</h3>
              <p class="text-sm text-stone-400 font-light">Accounting, audit, administration, and property management need to be budgeted for every year.</p>
            </div>
          </div>
          <div class="chart-wrap">
            <canvas id="costChart"></canvas>
          </div>
        </div>
      </div>
    </section>

    <section class="section-block max-w-7xl mx-auto px-6">
      <div class="text-center max-w-3xl mx-auto mb-16">
        <p class="text-[#7a3e04] text-xs uppercase tracking-[0.28em] font-bold mb-4">Advisory team</p>
        <h2 class="text-4xl font-bold mb-6">Who Does What?</h2>
        <p class="text-stone-600 font-light leading-relaxed">Build your team correctly from day one. The strength of the structure depends heavily on the quality of the professionals around you.</p>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
        <div class="premium-card p-8">
          <h3 class="text-xl font-bold mb-4">Financial Planner</h3>
          <p class="text-sm text-stone-600 font-light">Assesses whether an SMSF property strategy aligns with your goals, balance, time frame, and broader financial position.</p>
        </div>
        <div class="premium-card p-8">
          <h3 class="text-xl font-bold mb-4">SMSF Accountant</h3>
          <p class="text-sm text-stone-600 font-light">Sets up the fund, manages compliance, coordinates audit requirements, and helps keep the structure operating correctly.</p>
        </div>
        <div class="premium-card p-8">
          <h3 class="text-xl font-bold mb-4">Buyer's Agent</h3>
          <p class="text-sm text-stone-600 font-light">Sources and secures investment grade properties that meet SMSF compliance requirements and long term growth objectives.</p>
        </div>
        <div class="premium-card p-8">
          <h3 class="text-xl font-bold mb-4">Mortgage Broker</h3>
          <p class="text-sm text-stone-600 font-light">Assesses borrowing feasibility, coordinates lender requirements, and manages the finance process through to settlement.</p>
        </div>
        <div class="premium-card p-8">
          <h3 class="text-xl font-bold mb-4">Solicitor or Conveyancer</h3>
          <p class="text-sm text-stone-600 font-light">Handles the legal side of the purchase and makes sure contracts, transfers, and settlement documents are structured correctly.</p>
        </div>
        <div class="bg-black text-white p-8 border-t-2 border-t-[#7a3e04] flex items-center justify-center text-center">
          <p class="text-xs uppercase tracking-[0.2em] font-bold leading-loose">The decision to proceed should come from you, your planner, and your accountant first.</p>
        </div>
      </div>
    </section>

    <section class="section-block bg-stone-50">
      <div class="max-w-7xl mx-auto px-6">
        <div class="text-center max-w-3xl mx-auto mb-16">
          <p class="text-[#7a3e04] text-xs uppercase tracking-[0.28em] font-bold mb-4">Next step</p>
          <h2 class="text-4xl font-bold mb-6">Where to From Here?</h2>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-2 gap-px bg-stone-200 border border-stone-200">
          <div class="bg-white p-12">
            <div class="text-[10px] uppercase tracking-[0.24em] text-stone-400 font-bold mb-6">Option A</div>
            <h3 class="text-2xl font-bold mb-4">Still figuring it out?</h3>
            <p class="text-sm text-stone-600 font-light leading-relaxed mb-8">Speak with your financial planner and SMSF accountant first. Their role is to help determine whether this strategy is appropriate before any property is selected.</p>
            <ul class="space-y-4 text-sm text-stone-800 font-medium">
              <li class="flex items-start gap-3"><span class="w-1.5 h-1.5 bg-[#7a3e04] rounded-full mt-2"></span><span>Understand the structure properly</span></li>
              <li class="flex items-start gap-3"><span class="w-1.5 h-1.5 bg-[#7a3e04] rounded-full mt-2"></span><span>Get clarity on suitability and risk</span></li>
              <li class="flex items-start gap-3"><span class="w-1.5 h-1.5 bg-[#7a3e04] rounded-full mt-2"></span><span>Make an informed decision before acting</span></li>
            </ul>
          </div>
          <div class="bg-black text-white p-12">
            <div class="text-[10px] uppercase tracking-[0.24em] text-stone-500 font-bold mb-6">Option B</div>
            <h3 class="text-2xl font-bold mb-4">Ready to move?</h3>
            <p class="text-sm text-stone-400 font-light leading-relaxed mb-8">Once you have the green light from your planner and accountant, the next step is to assess feasibility, finance, and suitable property options.</p>
            <ul class="space-y-5 text-sm font-light">
              <li class="flex gap-4"><span class="text-[#b0a395] font-bold">01.</span><span>Confirm your borrowing position</span></li>
              <li class="flex gap-4"><span class="text-[#b0a395] font-bold">02.</span><span>Map the right property criteria</span></li>
              <li class="flex gap-4"><span class="text-[#b0a395] font-bold">03.</span><span>Build the right team around the transaction</span></li>
            </ul>
          </div>
        </div>
      </div>
    </section>

    <section id="contact" class="section-block max-w-7xl mx-auto px-6">
      <div class="text-center max-w-3xl mx-auto mb-16">
        <p class="text-[#7a3e04] text-xs uppercase tracking-[0.28em] font-bold mb-4">Contact</p>
        <h2 class="text-4xl font-bold mb-6">Book a Strategy Conversation</h2>
        <p class="text-stone-600 font-light leading-relaxed">Build your team correctly from day one. Start with a conversation about feasibility, structure, and the type of property that may suit your broader plan.</p>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
        <div class="premium-card p-8">
          <div class="text-[10px] uppercase tracking-[0.24em] text-stone-400 font-bold mb-5">Buyer's Agent</div>
          <h3 class="text-xl font-bold mb-1">Dereje Bushell</h3>
          <p class="text-sm text-stone-500 mb-6">Quantum Buyers Agents</p>
          <div class="space-y-2 text-sm text-stone-700">
            <a href="tel:0427338105" class="block hover:text-[#7a3e04]">0427 338 105</a>
            <a href="mailto:dereje@quantumbuyersagents.com" class="block hover:text-[#7a3e04] break-all">dereje@quantumbuyersagents.com</a>
          </div>
        </div>
        <div class="premium-card p-8">
          <div class="text-[10px] uppercase tracking-[0.24em] text-stone-400 font-bold mb-5">Mortgage Broker</div>
          <h3 class="text-xl font-bold mb-1">Jason Kuan</h3>
          <p class="text-sm text-stone-500 mb-6">Shern Advisory</p>
          <div class="space-y-2 text-sm text-stone-700">
            <a href="tel:0433147323" class="block hover:text-[#7a3e04]">0433 147 323</a>
            <a href="mailto:jason@shernadvisory.com.au" class="block hover:text-[#7a3e04] break-all">jason@shernadvisory.com.au</a>
          </div>
        </div>
        <div class="premium-card p-8">
          <div class="text-[10px] uppercase tracking-[0.24em] text-stone-400 font-bold mb-5">Financial Planner</div>
          <h3 class="text-xl font-bold mb-1">Ben Newman</h3>
          <p class="text-sm text-stone-500 mb-6">Seedli</p>
          <div class="space-y-2 text-sm text-stone-700">
            <a href="tel:0450138587" class="block hover:text-[#7a3e04]">0450 138 587</a>
            <a href="mailto:ben@seedli.com.au" class="block hover:text-[#7a3e04] break-all">ben@seedli.com.au</a>
          </div>
        </div>
      </div>
    </section>
  </main>

  <footer class="py-14 px-6 border-t border-stone-200">
    <div class="max-w-5xl mx-auto text-center">
      <p class="text-[11px] uppercase tracking-[0.14em] text-stone-400 leading-relaxed">
        This page is general information only and should not be relied on as financial, legal, or tax advice. Individual circumstances vary and professional advice should always be obtained before making any decisions.
      </p>
    </div>
  </footer>

  <script>
    document.addEventListener('DOMContentLoaded', function () {
      const lrbaCtx = document.getElementById('lrbaChart').getContext('2d');
      new Chart(lrbaCtx, {
        type: 'bar',
        data: {
          labels: ['SMSF Equity', 'LRBA Finance'],
          datasets: [{
            data: [25, 75],
            backgroundColor: ['#b0a395', '#7a3e04'],
            borderRadius: 6,
            barThickness: 38
          }]
        },
        options: {
          indexAxis: 'y',
          responsive: true,
          maintainAspectRatio: false,
          plugins: {
            legend: { display: false }
          },
          scales: {
            x: {
              display: false,
              max: 100
            },
            y: {
              grid: { display: false },
              ticks: {
                color: '#475b6d',
                font: { size: 11, weight: '700' }
              }
            }
          }
        }
      });

      const costCtx = document.getElementById('costChart').getContext('2d');
      new Chart(costCtx, {
        type: 'doughnut',
        data: {
          labels: ['Setup', 'Ongoing Admin', 'Property Management'],
          datasets: [{
            data: [40, 35, 25],
            backgroundColor: ['#7a3e04', '#475b6d', '#b0a395'],
            borderColor: '#000000',
            borderWidth: 3
          }]
        },
        options: {
          responsive: true,
          maintainAspectRatio: false,
          cutout: '76%',
          plugins: {
            legend: {
              position: 'bottom',
              labels: {
                color: '#d6d3d1',
                font: { size: 11, weight: '700' },
                padding: 20
              }
            }
          }
        }
      });
    });
  </script>
</body>
</html>
