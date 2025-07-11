import React, { useState, useEffect, useRef } from 'react';

// --- Placeholder UI Components (Remain the same) ---
const Card = ({ children, className = '', ...props }) => (<div className={`border border-gray-200 rounded-lg shadow-sm bg-white text-gray-900 ${className}`} {...props}>{children}</div>);
const CardHeader = ({ children, className = '', ...props }) => (<div className={`flex flex-col space-y-1.5 p-4 md:p-5 ${className}`} {...props}>{children}</div>);
const CardContent = ({ children, className = '', ...props }) => (<div className={`p-4 md:p-5 pt-0 ${className}`} {...props}>{children}</div>);
const CardFooter = ({ children, className = '', ...props }) => (<div className={`flex flex-wrap items-center justify-between gap-2 p-4 md:p-5 pt-0 ${className}`} {...props}>{children}</div>);
const Badge = ({ children, className = '', variant = 'default', ...props }) => {
  const variantClasses = { default: 'border-transparent bg-gray-900 text-white hover:bg-gray-700', secondary: 'border-transparent bg-gray-100 text-gray-800 hover:bg-gray-200', outline: 'text-gray-600 border border-gray-300', success: 'border-transparent bg-green-100 text-green-800', warning: 'border-transparent bg-amber-100 text-amber-800', highlight: 'border-transparent bg-blue-100 text-blue-800 font-semibold px-3 py-1 text-xs md:text-sm', };
  return (<div className={`inline-flex items-center rounded-full border px-2.5 py-0.5 text-xs font-medium transition-colors focus:outline-none focus:ring-2 focus:ring-ring focus:ring-offset-2 ${variantClasses[variant]} ${className}`} {...props}>{children}</div>);
};
const Button = ({ children, className = '', variant = 'default', onClick, ...props }) => {
  const variantClasses = { default: 'bg-gray-900 text-white hover:bg-gray-700 focus-visible:ring-gray-900', outline: 'border border-gray-300 bg-white hover:bg-gray-100 text-gray-700 focus-visible:ring-gray-400', success: 'bg-green-600 text-white hover:bg-green-700 focus-visible:ring-green-500', destructive: 'bg-red-600 text-white hover:bg-red-700 focus-visible:ring-red-600', secondary: 'bg-gray-100 text-gray-900 hover:bg-gray-200 focus-visible:ring-gray-400', ghost: 'hover:bg-gray-100 text-gray-900 focus-visible:ring-gray-400', link: 'text-blue-600 underline-offset-4 hover:underline focus-visible:ring-blue-500', };
  return (<button className={`inline-flex items-center justify-center whitespace-nowrap rounded-md text-sm font-medium ring-offset-background transition-colors focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-offset-2 disabled:pointer-events-none disabled:opacity-50 h-9 px-3 md:h-9 md:px-4 md:py-2 ${variantClasses[variant]} ${className}`} onClick={onClick} {...props}>{children}</button>);
};
const Progress = ({ value = 0, className = '', ...props }) => (<div className={`relative h-1.5 w-full overflow-hidden rounded-full bg-gray-200 ${className}`}><div className="h-full w-full flex-1 bg-gray-600 transition-all" style={{ transform: `translateX(-${100 - (value || 0)}%)` }} /></div>);

// --- Placeholder Icons (Remain the same) ---
const FlagIcon = ({ className = '', ...props }) => (<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className={`lucide lucide-flag ${className}`} {...props}><path d="M4 15s1-1 4-1 5 2 8 2 4-1 4-1V3s-1 1-4 1-5-2-8-2-4 1-4 1z" /><line x1="4" x2="4" y1="22" y2="15" /></svg>);
const SearchIcon = ({ className = '', ...props }) => (<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className={`lucide lucide-search ${className}`} {...props}><circle cx="11" cy="11" r="8"></circle><line x1="21" y1="21" x2="16.65" y2="16.65"></line></svg>);
const WalletIcon = ({ className = '', ...props }) => (<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className={`lucide lucide-wallet ${className}`} {...props}><path d="M21 12V7H5a2 2 0 0 1 0-4h14v4"></path><path d="M3 5v14a2 2 0 0 0 2 2h16v-5"></path><path d="M18 12a2 2 0 0 0 0 4h4v-4Z"></path></svg>);
const ShoppingBasketIcon = ({ className = '', ...props }) => (<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className={`lucide lucide-shopping-basket ${className}`} {...props}><path d="m5 11 4-7"></path><path d="m19 11-4-7"></path><path d="M2 11h20"></path><path d="m3.5 11 1.6 7.4a2 2 0 0 0 2 1.6h9.8c.9 0 1.8-.7 2-1.6l1.7-7.4"></path><path d="m9 11 1 9"></path><path d="M4.5 15.5h15"></path><path d="m15 11-1 9"></path></svg>);
const ChevronDownIcon = ({ className = '', ...props }) => (<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className={`lucide lucide-chevron-down ${className}`} {...props}><path d="m6 9 6 6 6-6"></path></svg>);
const ChevronLeftIcon = ({ className = '', ...props }) => (<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className={`lucide lucide-chevron-left ${className}`} {...props}><path d="m15 18-6-6 6-6"></path></svg>);
const FilterIcon = ({ className = '', ...props }) => (<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className={`lucide lucide-filter ${className}`} {...props}><polygon points="22 3 2 3 10 12.46 10 19 14 21 14 12.46 22 3"></polygon></svg>);
const XIcon = ({ className = '', ...props }) => (<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className={`lucide lucide-x ${className}`} {...props}><path d="M18 6 6 18"></path><path d="m6 6 12 12"></path></svg>);
const TagIcon = ({ className = '', ...props }) => (<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className={`lucide lucide-tag ${className}`} {...props}><path d="M12.586 2.586A2 2 0 0 0 11.172 2H4a2 2 0 0 0-2 2v7.172a2 2 0 0 0 .586 1.414l8.704 8.704a2.426 2.426 0 0 0 3.432 0l6.568-6.568a2.426 2.426 0 0 0 0-3.432l-8.704-8.704Z"/><line x1="7" x2="7.01" y1="7" y2="7"/></svg>);
const LayoutListIcon = ({ className = '', ...props }) => (<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className={`lucide lucide-layout-list ${className}`} {...props}><rect width="7" height="7" x="3" y="3" rx="1"/><rect width="7" height="7" x="3" y="14" rx="1"/><path d="M14 4h7"/><path d="M14 9h7"/><path d="M14 15h7"/><path d="M14 20h7"/></svg>);
const CalendarIcon = ({ className = '', ...props }) => (<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className={`lucide lucide-calendar ${className}`} {...props}><rect width="18" height="18" x="3" y="4" rx="2" ry="2"/><line x1="16" x2="16" y1="2" y2="6"/><line x1="8" x2="8" y1="2" y2="6"/><line x1="3" x2="21" y1="10" y2="10"/></svg>);
const BriefcaseIcon = ({ className = '', ...props }) => (<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className={`lucide lucide-briefcase ${className}`} {...props}><rect width="20" height="14" x="2" y="7" rx="2" ry="2"/><path d="M16 21V5a2 2 0 0 0-2-2h-4a2 2 0 0 0-2 2v16"/></svg>);
const LayoutDashboardIcon = ({ className = '', ...props }) => (<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className={`lucide lucide-layout-dashboard ${className}`} {...props}><rect width="7" height="9" x="3" y="3" rx="1"/><rect width="7" height="5" x="14" y="3" rx="1"/><rect width="7" height="9" x="14" y="12" rx="1"/><rect width="7" height="5" x="3" y="16" rx="1"/></svg>);
const ActivityIcon = ({ className = '', ...props }) => (<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className={`lucide lucide-activity ${className}`} {...props}><path d="M22 12h-4l-3 9L9 3l-3 9H2"/></svg>);
const FileTextIcon = ({ className = '', ...props }) => (<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className={`lucide lucide-file-text ${className}`} {...props}><path d="M14.5 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7.5L14.5 2z"/><polyline points="14 2 14 8 20 8"/><line x1="16" x2="8" y1="13" y2="13"/><line x1="16" x2="8" y1="17" y2="17"/><line x1="10" x2="8" y1="9" y2="9"/></svg>);
const NotebookTextIcon = ({ className = '', ...props }) => (<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className={`lucide lucide-notebook-text ${className}`} {...props}><path d="M2 6h4"/><path d="M2 10h4"/><path d="M2 14h4"/><path d="M2 18h4"/><rect width="16" height="20" x="4" y="2" rx="2"/><path d="M9.5 8h5"/><path d="M9.5 12H18"/><path d="M9.5 16H18"/></svg>);
const BrainCircuitIcon = ({ className = '', ...props }) => (<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className={`lucide lucide-brain-circuit ${className}`} {...props}><path d="M12 5a3 3 0 1 0-5.997.125 4 4 0 0 0-2.526 5.77 4 4 0 0 0 .556 6.588 4 4 0 0 0 7.939 1.499A3 3 0 1 0 12 5Z"/><path d="M14.5 5.5a3 3 0 1 0 3 5.875 4 4 0 0 0 2.526 5.77 4 4 0 0 0-.556 6.588 4 4 0 0 0-7.939 1.499A3 3 0 1 0 14.5 5.5Z"/><path d="M11 12a1 1 0 1 0-2 0 1 1 0 0 0 2 0Z"/><path d="M15 13a1 1 0 1 0-2 0 1 1 0 0 0 2 0Z"/><path d="M13 7.5a1 1 0 1 0-2 0 1 1 0 0 0 2 0Z"/><path d="M11 16.5a1 1 0 1 0-2 0 1 1 0 0 0 2 0Z"/><path d="M16 16.5a1 1 0 1 0-2 0 1 1 0 0 0 2 0Z"/></svg>);


// --- Lead Card Component (More Compact) ---

interface Lead { id: string; name: string; countryCode: string; visaCategory: string; readiness: 'Exploring' | 'Preparing' | 'Ready to File'; readinessScore: number; legalFeeRange?: [number, number]; investmentAmount: string; age: number; education: string; languageProficiency: string; matchScore: number; price: number; views: number; }
interface LeadCardListProps { leads: Lead[]; onDetails: (leadId: string) => void; onSave: (leadId: string) => void; onPurchase: (leadId: string) => void; }
const formatName = (fullName: string): string => { const parts = fullName.trim().split(' '); if (parts.length < 2) return fullName; const firstName = parts[0]; const lastNameInitial = parts[parts.length - 1][0]; return `${firstName} ${lastNameInitial}.`; };

function LeadCardList({ leads, onDetails, onSave, onPurchase }: LeadCardListProps) {
  if (!leads || leads.length === 0) { return <p className="text-center text-gray-500 col-span-full py-10">No leads found matching your criteria.</p>; }
  return (
    <>
      {leads.map((lead) => {
        let minFee = 0, maxFee = 0; if (Array.isArray(lead.legalFeeRange) && lead.legalFeeRange.length === 2 && typeof lead.legalFeeRange[0] === 'number' && typeof lead.legalFeeRange[1] === 'number') { [minFee, maxFee] = lead.legalFeeRange; }
        const borderColorClass = lead.matchScore >= 80 ? 'border-green-500' : lead.matchScore >= 50 ? 'border-amber-500' : 'border-gray-200';
        const readinessVariant = lead.readiness === 'Ready to File' ? 'success' : lead.readiness === 'Preparing' ? 'warning' : 'outline';
        const displayName = formatName(lead.name);
        return (
          <Card key={lead.id} className={`border-2 ${borderColorClass} flex flex-col justify-between h-full transition-shadow hover:shadow-md`}>
            <div> {/* Content wrapper */}
              <CardHeader className="flex flex-row justify-between items-start space-x-3 pb-3"><div className="flex items-center space-x-2 flex-grow min-w-0"><FlagIcon className="h-4 w-4 text-gray-400 flex-shrink-0" /><h3 className="text-base font-semibold text-gray-800 truncate" title={lead.name}>{displayName}</h3></div><Badge variant="highlight" className="flex-shrink-0 whitespace-nowrap">{lead.matchScore}% Match</Badge></CardHeader>
              <CardContent className="space-y-2.5 md:space-y-3"><div className="flex flex-wrap items-center gap-x-3 gap-y-1 text-xs"><Badge variant="outline">{lead.visaCategory}</Badge><Badge variant={readinessVariant}>{lead.readiness}</Badge>{(minFee > 0 || maxFee > 0) && (<span className="text-gray-500">Fees: ${minFee.toLocaleString()}–${maxFee.toLocaleString()}</span>)}</div><div className="space-y-1"><div className="flex justify-between items-center text-xs mb-0.5"><span className="font-medium text-gray-500">Readiness</span><span className="font-semibold text-gray-700">{lead.readinessScore}%</span></div><Progress id={`readiness-${lead.id}`} value={lead.readinessScore} aria-label={`Readiness score: ${lead.readinessScore}%`} /></div><div className="text-xs text-gray-600 space-y-1"><div className="flex flex-wrap gap-x-3 gap-y-0.5"><span>Origin: <strong className="font-medium text-gray-700">{lead.countryCode}</strong></span><span>Age: <strong className="font-medium text-gray-700">{lead.age}</strong></span><span>Education: <strong className="font-medium text-gray-700">{lead.education}</strong></span><span>Language: <strong className="font-medium text-gray-700">{lead.languageProficiency}</strong></span></div><div>Investment: <strong className="font-medium text-gray-700">{lead.investmentAmount}</strong></div></div></CardContent>
            </div> {/* End Content wrapper */}
            <CardFooter className="pt-2.5 md:pt-3 mt-auto"><div className="flex items-center gap-2"><Button variant="outline" onClick={() => onDetails(lead.id)} className="text-xs" title="View lead details">Details</Button><Button variant="outline" onClick={() => onSave(lead.id)} className="text-xs" title="Save this lead for later">Save</Button></div><Button onClick={() => onPurchase(lead.id)} className="text-xs font-semibold" title={`Purchase this lead for $${lead.price.toFixed(1)}`}>Purchase (${lead.price.toFixed(1)})</Button></CardFooter>
          </Card>
        );
      })}
    </>
  );
}

// --- Filter Panel Component ---
interface FilterPanelProps { onFilterChange: (filterName: string, value: any) => void; onClose: () => void; }
const FilterDropdown = ({ label, name, options, onChange, value }: { label: string, name: string, options: string[], onChange: (event: React.ChangeEvent<HTMLSelectElement>) => void, value?: string }) => (<div className="space-y-1.5"><label htmlFor={name} className="block text-sm font-medium text-gray-700">{label}</label><div className="relative"><select id={name} name={name} onChange={onChange} value={value || ""} className="appearance-none block w-full pl-3 pr-10 py-2 text-sm border border-gray-300 bg-white rounded-md shadow-sm focus:outline-none focus:ring-1 focus:ring-blue-500 focus:border-blue-500"><option value="" disabled={!value} className="text-gray-400">{label === "" ? "Sort By..." : "Select..."}</option>{options.map(option => <option key={option} value={option}>{option}</option>)}</select><ChevronDownIcon className="absolute right-3 top-1/2 transform -translate-y-1/2 h-4 w-4 text-gray-400 pointer-events-none" /></div></div>);
const RangeFilter = ({ label, namePrefix, onChange }: { label: string, namePrefix: string, onChange: (event: React.ChangeEvent<HTMLInputElement>) => void }) => (<div className="space-y-1.5"><label className="block text-sm font-medium text-gray-700">{label}</label><div className="flex items-center gap-2"><input type="number" name={`${namePrefix}Min`} id={`${namePrefix}Min`} onChange={onChange} placeholder="Min" className="block w-full px-3 py-2 text-sm border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-1 focus:ring-blue-500 focus:border-blue-500" /><span className="text-gray-500">–</span><input type="number" name={`${namePrefix}Max`} id={`${namePrefix}Max`} onChange={onChange} placeholder="Max" className="block w-full px-3 py-2 text-sm border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-1 focus:ring-blue-500 focus:border-blue-500" /></div></div>);

// FilterPanel: Now part of the flex layout, not absolutely positioned
function FilterPanel({ onFilterChange, onClose }: FilterPanelProps) {
    const handleChange = (event: React.ChangeEvent<HTMLSelectElement | HTMLInputElement>) => { const { name, value } = event.target; onFilterChange(name, value); };
    return (
        // Width w-64, sticky positioning below top bar, higher z-index than main sidebar
        // flex-shrink-0 prevents it from shrinking
        <aside className={`bg-white border-r border-gray-200 flex-shrink-0 w-64 p-4 sticky top-16 h-[calc(100vh-4rem)] z-25 transition-all duration-300 ease-in-out flex flex-col`}>
            <div className="flex justify-between items-center mb-4 flex-shrink-0">
                 <h2 className="text-lg font-semibold text-gray-800">Filter</h2>
                 {/* Close button might still be useful for clarity, even if filter button also closes it */}
                 <Button variant="ghost" onClick={onClose} className="p-1 h-auto">
                     <XIcon className="h-5 w-5 text-gray-500" />
                 </Button>
            </div>
            {/* Scrollable filter content */}
            <div className="space-y-4 overflow-y-auto pb-4 flex-grow">
                <FilterDropdown label="Home country" name="homeCountry" options={['USA', 'Canada', 'UK', 'Australia', 'Germany', 'Other']} onChange={handleChange} />
                <FilterDropdown label="Education" name="education" options={["Associate", "Bachelor's", "Master's", "PhD", "Other"]} onChange={handleChange} />
                <FilterDropdown label="Occupation" name="occupation" options={['Technology', 'Healthcare', 'Finance', 'Management', 'Other']} onChange={handleChange} />
                <FilterDropdown label="Asset Range" name="assetRange" options={['$0-$100k', '$100k-$500k', '$500k-$1M', '$1M+']} onChange={handleChange} />
                <FilterDropdown label="Language" name="language" options={['English', 'Spanish', 'French', 'German', 'Mandarin', 'Other']} onChange={handleChange} />
                <FilterDropdown label="Status" name="status" options={['Exploring', 'Preparing', 'Ready to File']} onChange={handleChange} />
                <FilterDropdown label="Interested In" name="interest" options={['EB-5', 'Start-up Visa', 'Skilled Worker', 'Global Talent']} onChange={handleChange} />
                <RangeFilter label="Lead Price" namePrefix="leadPrice" onChange={handleChange} />
                <div className="pt-4 border-t border-gray-200">
                     <Button variant="default" className="w-full">Apply Filters</Button>
                     <Button variant="outline" className="w-full mt-2">Reset Filters</Button>
                </div>
            </div>
        </aside>
    );
}

// --- Top Bar Component ---
interface TopBarProps { creditAmount: number; basketItemCount: number; onSearchChange: (searchTerm: string) => void; }
function TopBar({ creditAmount, basketItemCount, onSearchChange }: TopBarProps) {
    const [searchTerm, setSearchTerm] = useState('');
    const handleInputChange = (event: React.ChangeEvent<HTMLInputElement>) => { setSearchTerm(event.target.value); onSearchChange(event.target.value); };
    return (
        <div className="flex items-center justify-between p-4 bg-white border-b border-gray-200 sticky top-0 z-40">
            <div className="text-xl font-bold text-gray-800">Lead Marketplace</div>
            <div className="flex items-center space-x-4 md:space-x-6">
                <div className="relative"><input type="text" placeholder="Search leads..." value={searchTerm} onChange={handleInputChange} className="pl-10 pr-4 py-2 w-48 md:w-64 border border-gray-300 rounded-md text-sm focus:outline-none focus:ring-1 focus:ring-blue-500 focus:border-blue-500" /><SearchIcon className="absolute left-3 top-1/2 transform -translate-y-1/2 h-5 w-5 text-gray-400" /></div>
                <div className="flex items-center space-x-2 text-sm text-gray-700"><WalletIcon className="h-5 w-5 text-gray-500" /><span className="font-medium">${creditAmount.toFixed(2)}</span></div>
                <button className="relative p-2 rounded-full hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-gray-500"><ShoppingBasketIcon className="h-6 w-6 text-gray-600" />{basketItemCount > 0 && (<span className="absolute top-0 right-0 inline-flex items-center justify-center px-2 py-1 text-xs font-bold leading-none text-red-100 transform translate-x-1/2 -translate-y-1/2 bg-red-600 rounded-full">{basketItemCount}</span>)}</button>
            </div>
        </div>
    );
}

// --- Controls Bar Component (Above Cards) ---
interface LeadControlsProps { onFilterToggle: () => void; onSortChange: (event: React.ChangeEvent<HTMLSelectElement>) => void; sortValue: string; }
function LeadControls({ onFilterToggle, onSortChange, sortValue }: LeadControlsProps) {
    const sortOptions = ['Best Match', 'Match Score', 'Readiness', 'Price (Low-High)', 'Price (High-Low)', 'Age'];
    return (
        <div className="flex items-center justify-between mb-4 px-1 flex-shrink-0"> {/* Prevent controls from shrinking */}
            <Button variant="outline" onClick={onFilterToggle} className="flex items-center gap-2"><FilterIcon className="h-4 w-4" />Filter</Button>
            <div className="w-48"><FilterDropdown label="" name="sortBy" options={sortOptions} onChange={onSortChange} value={sortValue} /></div>
        </div>
    );
}

// --- Main Sidebar Component ---
interface MainSidebarProps { isExpanded: boolean; onToggle: () => void; }
function MainSidebar({ isExpanded, onToggle }: MainSidebarProps) {
    const menuItems = [ { name: 'Buy Leads', icon: TagIcon, active: true }, { name: 'CRM', icon: LayoutListIcon, active: false }, { name: 'Calendar', icon: CalendarIcon, active: false }, { name: 'Jobs', icon: BriefcaseIcon, active: false }, { name: 'Dashboard', icon: LayoutDashboardIcon, active: false }, { name: 'Activities', icon: ActivityIcon, active: false }, { name: 'Cases', icon: FileTextIcon, active: false }, { name: 'Templates', icon: NotebookTextIcon, active: false }, { name: 'Ai History', icon: BrainCircuitIcon, active: false }, ];
    return (
        <aside className={`bg-white border-r border-gray-200 flex-shrink-0 flex flex-col transition-width duration-300 ease-in-out sticky top-16 h-[calc(100vh-4rem)] z-20 ${isExpanded ? 'w-60' : 'w-16'}`}>
            <div className={`flex items-center p-4 border-b border-gray-200 ${isExpanded ? 'justify-between' : 'justify-center'}`}>
                {isExpanded && <span className="text-lg font-semibold text-gray-800">Globali</span>}
                <Button variant="ghost" onClick={onToggle} className="p-1 h-auto"><ChevronLeftIcon className={`h-5 w-5 text-gray-600 transition-transform duration-300 ${!isExpanded ? 'rotate-180' : ''}`} /></Button>
            </div>
            <nav className="flex-1 overflow-y-auto py-4">
                <ul className="space-y-1 px-2">{menuItems.map(item => (<li key={item.name}><a href="#" className={`flex items-center p-2 rounded-md text-sm font-medium transition-colors ${item.active ? 'bg-blue-50 text-blue-700' : 'text-gray-600 hover:bg-gray-100 hover:text-gray-900'} ${!isExpanded ? 'justify-center' : ''}`}><item.icon className={`h-5 w-5 flex-shrink-0 ${isExpanded ? 'mr-3' : 'mr-0'}`} />{isExpanded && <span>{item.name}</span>}</a></li>))}</ul>
            </nav>
        </aside>
    );
}


// --- Main App Component (Integrating Layout) ---
export default function App() {
  // --- State Management ---
  const [allLeads, setAllLeads] = useState<Lead[]>([]);
  const [filteredLeads, setFilteredLeads] = useState<Lead[]>([]);
  const [isLoading, setIsLoading] = useState(true);
  const [searchTerm, setSearchTerm] = useState('');
  const [filters, setFilters] = useState<Record<string, any>>({ sortBy: 'Best Match' }); // Default sort
  const [isFilterPanelOpen, setIsFilterPanelOpen] = useState(false); // Filter panel closed by default
  const [isMainMenuExpanded, setIsMainMenuExpanded] = useState(true); // Main menu expanded by default

  // --- Sample Data Generation ---
  useEffect(() => {
    const generateRandomPrice = () => parseFloat((Math.random() * (50.0 - 10.0) + 10.0).toFixed(1));
    const baseSampleLeads: Omit<Lead, 'price'>[] = [ { id: 'lead-1', name: 'Alice Johnson', countryCode: 'US', visaCategory: 'EB-5 Investor', readiness: 'Ready to File', readinessScore: 90, legalFeeRange: [15000, 25000], investmentAmount: '$800k+', age: 45, education: "Master's", languageProficiency: 'Fluent', matchScore: 95, views: 12 }, { id: 'lead-2', name: 'Bob Williams', countryCode: 'CA', visaCategory: 'Start-up Visa', readiness: 'Preparing', readinessScore: 65, legalFeeRange: [8000, 12000], investmentAmount: '$200k+', age: 38, education: "Bachelor's", languageProficiency: 'Advanced', matchScore: 70, views: 5 }, { id: 'lead-3', name: 'Charlie Brown', countryCode: 'GB', visaCategory: 'Skilled Worker', readiness: 'Exploring', readinessScore: 30, investmentAmount: 'N/A', age: 29, education: "Associate", languageProficiency: 'Intermediate', matchScore: 40, views: 2 }, { id: 'lead-4', name: 'Diana Prince', countryCode: 'AU', visaCategory: 'Global Talent', readiness: 'Ready to File', readinessScore: 95, legalFeeRange: [10000, 18000], investmentAmount: '$150k+', age: 35, education: "PhD", languageProficiency: 'Native', matchScore: 88, views: 25 }, { id: 'lead-5', name: 'Ethan Hunt', countryCode: 'DE', visaCategory: 'Investor Visa', readiness: 'Preparing', readinessScore: 75, investmentAmount: '$500k+', age: 52, education: "Bachelor's", languageProficiency: 'Fluent', matchScore: 65, views: 8 }, { id: 'lead-6', name: 'Fiona Gallagher', countryCode: 'US', visaCategory: 'EB-5 Investor', readiness: 'Exploring', readinessScore: 45, investmentAmount: '$900k+', age: 31, education: "High School", languageProficiency: 'Native', matchScore: 55, views: 1 }, { id: 'lead-7', name: 'George Costanza', countryCode: 'US', visaCategory: 'Skilled Worker', readiness: 'Preparing', readinessScore: 60, legalFeeRange: [5000, 9000], investmentAmount: '<$100k', age: 48, education: "Bachelor's", languageProficiency: 'Native', matchScore: 50, views: 15 }, ];
    const leadsWithPrices = baseSampleLeads.map(lead => ({ ...lead, price: generateRandomPrice() }));
    setTimeout(() => { setAllLeads(leadsWithPrices); setIsLoading(false); }, 1000);
  }, []);


  // --- Filtering and Sorting Logic ---
  useEffect(() => {
      let result = [...allLeads];
      if (searchTerm) { result = result.filter(lead => lead.name.toLowerCase().includes(searchTerm.toLowerCase())); }
      Object.keys(filters).forEach(key => {
          const filterValue = filters[key];
          if (filterValue && key !== 'sortBy') {
              result = result.filter(lead => {
                  switch (key) {
                      case 'homeCountry': return lead.countryCode === filterValue;
                      case 'status': return lead.readiness === filterValue;
                      case 'education': return lead.education === filterValue;
                      case 'language': return lead.languageProficiency === filterValue;
                      default: return true;
                  }
              });
          }
      });
      const sortBy = filters.sortBy || 'Best Match';
      if (sortBy) {
          result.sort((a, b) => {
              switch (sortBy) {
                  case 'Best Match': const weightMap = { 'Ready to File': 1.2, Preparing: 1.0, Exploring: 0.8 }; const aScore = a.matchScore * (weightMap[a.readiness] || 1); const bScore = b.matchScore * (weightMap[b.readiness] || 1); return bScore - aScore;
                  case 'Match Score': return b.matchScore - a.matchScore;
                  case 'Readiness': const readinessValue = { 'Ready to File': 3, 'Preparing': 2, 'Exploring': 1 }; return (readinessValue[b.readiness] || 0) - (readinessValue[a.readiness] || 0);
                  case 'Price (Low-High)': return a.price - b.price;
                  case 'Price (High-Low)': return b.price - a.price;
                  case 'Age': return a.age - b.age;
                  default: return 0;
              }
          });
      }
      setFilteredLeads(result);
  }, [searchTerm, filters, allLeads]);


  // --- Action Handlers ---
  const handleDetails = (leadId: string) => { alert(`Showing details for: ${leadId}`); };
  const handleSave = (leadId: string) => { alert(`Saving lead: ${leadId}`); };
  const handlePurchase = (leadId: string) => { alert(`Purchase initiated for ${leadId}`); };
  const handleSearchChange = (term: string) => { setSearchTerm(term); };
  const handleFilterChange = (filterName: string, value: any) => { setFilters(prevFilters => ({ ...prevFilters, [filterName]: value })); };
  const handleSortChange = (event: React.ChangeEvent<HTMLSelectElement>) => { handleFilterChange('sortBy', event.target.value); };

  // Updated Toggle Logic for coordinated sidebars
  const toggleFilterPanel = () => {
      const openingFilter = !isFilterPanelOpen;
      setIsFilterPanelOpen(openingFilter);
      // If opening filter, ensure main menu is collapsed
      if (openingFilter) {
          setIsMainMenuExpanded(false);
      } else {
          // Re-expand main menu when filter closes
          setIsMainMenuExpanded(true);
      }
  };

  const toggleMainMenu = () => {
      const expandingMenu = !isMainMenuExpanded;
      setIsMainMenuExpanded(expandingMenu);
      // If expanding main menu, ensure filter panel is closed
      if (expandingMenu && isFilterPanelOpen) {
          setIsFilterPanelOpen(false);
      }
  };

  // Placeholder values
  const userCredit = 1250.75;
  const itemsInBasket = 3;


  return (
    <div className="min-h-screen bg-gray-100 font-sans flex flex-col"> {/* Ensure App takes full height */}
      <script src="https://cdn.tailwindcss.com"></script>
      <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet" />
      <style>{`
        body { font-family: 'Inter', sans-serif; background-color: #f3f4f6; overflow-x: hidden; }
        /* Backdrop for mobile filter */
        .filter-backdrop { position: fixed; inset: 0; background-color: rgba(0, 0, 0, 0.5); z-index: 25; opacity: 0; transition: opacity 0.3s ease-in-out; pointer-events: none; }
        .filter-backdrop.open { opacity: 1; pointer-events: auto; }
      `}</style>

      {/* Sticky Top Bar */}
       <TopBar creditAmount={userCredit} basketItemCount={itemsInBasket} onSearchChange={handleSearchChange} />

      {/* Main Layout with Main Sidebar */}
      <div className="flex flex-1 overflow-hidden"> {/* Allow content to scroll */}
          {/* Main Sidebar */}
          <MainSidebar isExpanded={isMainMenuExpanded} onToggle={toggleMainMenu} />

          {/* Conditionally render Filter Panel as a sibling */}
          {isFilterPanelOpen && (
              <FilterPanel onFilterChange={handleFilterChange} onClose={toggleFilterPanel} />
          )}

          {/* Main Content Area (Takes remaining space) */}
          <div className="flex-1 flex flex-col overflow-y-auto"> {/* Handles scrolling for controls + cards */}
             <main className="p-4 md:p-6 w-full">
                 {/* Controls Bar (Filter Toggle & Sort) */}
                 <LeadControls
                     onFilterToggle={toggleFilterPanel}
                     onSortChange={handleSortChange}
                     sortValue={filters.sortBy || 'Best Match'}
                 />
                 {/* Card Grid - Single column */}
                 {isLoading ? (
                     <p className="text-center text-gray-500 py-10">Loading leads...</p>
                 ) : (
                     <div className="grid grid-cols-1 gap-5 md:gap-6">
                         <LeadCardList
                             leads={filteredLeads}
                             onDetails={handleDetails}
                             onSave={handleSave}
                             onPurchase={handlePurchase}
                         />
                     </div>
                 )}
             </main>
          </div>
      </div>
    </div>
  );
}
