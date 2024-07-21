import React, { useState, useEffect } from 'react';
import { LineChart, Line, XAxis, YAxis, CartesianGrid, Tooltip, Legend, ResponsiveContainer } from 'recharts';
import { AlertCircle, DollarSign, TrendingUp, List } from 'lucide-react';
import { Card, CardHeader, CardContent } from '@/components/ui/card';
import { Alert, AlertDescription, AlertTitle } from '@/components/ui/alert';

// Mock data - replace with actual API calls in a real application
const mockFinancialData = [
  { month: 'Jan', revenue: 50000, expenses: 40000 },
  { month: 'Feb', revenue: 55000, expenses: 42000 },
  { month: 'Mar', revenue: 60000, expenses: 45000 },
  { month: 'Apr', revenue: 58000, expenses: 44000 },
  { month: 'May', revenue: 62000, expenses: 46000 },
];

const mockKPIs = [
  { name: 'Monthly Recurring Revenue', value: '$62,000', target: '$60,000', status: 'On Track' },
  { name: 'Customer Acquisition Cost', value: '$500', target: '$450', status: 'Needs Attention' },
  { name: 'Customer Lifetime Value', value: '$5,000', target: '$4,500', status: 'On Track' },
];

const mockInsights = [
  { type: 'Prediction', description: 'Revenue expected to grow by 15% next quarter based on current trends.' },
  { type: 'Recommendation', description: 'Consider increasing marketing budget for Product X to capitalize on growing market demand.' },
  { type: 'Alert', description: 'Expense in Department Y is 20% above projections. Review required.' },
];

const CEODashboard = () => {
  const [financialData, setFinancialData] = useState([]);
  const [kpis, setKPIs] = useState([]);
  const [insights, setInsights] = useState([]);

  useEffect(() => {
    // Simulating API calls - replace with actual data fetching in a real application
    setFinancialData(mockFinancialData);
    setKPIs(mockKPIs);
    setInsights(mockInsights);
  }, []);

  return (
    <div className="p-4 max-w-7xl mx-auto">
      <h1 className="text-3xl font-bold mb-6">CEO Dashboard</h1>
      
      <div className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4 mb-6">
        {kpis.map((kpi, index) => (
          <Card key={index}>
            <CardHeader>{kpi.name}</CardHeader>
            <CardContent>
              <div className="text-2xl font-bold">{kpi.value}</div>
              <div className={`text-sm ${kpi.status === 'On Track' ? 'text-green-500' : 'text-red-500'}`}>
                {kpi.status} (Target: {kpi.target})
              </div>
            </CardContent>
          </Card>
        ))}
      </div>

      <Card className="mb-6">
        <CardHeader>Revenue vs Expenses</CardHeader>
        <CardContent>
          <ResponsiveContainer width="100%" height={300}>
            <LineChart data={financialData}>
              <CartesianGrid strokeDasharray="3 3" />
              <XAxis dataKey="month" />
              <YAxis />
              <Tooltip />
              <Legend />
              <Line type="monotone" dataKey="revenue" stroke="#8884d8" />
              <Line type="monotone" dataKey="expenses" stroke="#82ca9d" />
            </LineChart>
          </ResponsiveContainer>
        </CardContent>
      </Card>

      <Card>
        <CardHeader>AI Insights</CardHeader>
        <CardContent>
          {insights.map((insight, index) => (
            <Alert key={index} className="mb-4">
              <AlertCircle className="h-4 w-4" />
              <AlertTitle>{insight.type}</AlertTitle>
              <AlertDescription>
                {insight.description}
              </AlertDescription>
            </Alert>
          ))}
        </CardContent>
      </Card>
    </div>
  );
};

export default CEODashboard;
